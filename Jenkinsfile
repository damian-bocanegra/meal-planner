pipeline {
  agent any
  stages {
    stage('Build') { 
      steps {
        echo 'Executing yarn'
        nodejs('Node-14.10.1') {
          sh 'yarn install'
        }
      }
    }
  }
}