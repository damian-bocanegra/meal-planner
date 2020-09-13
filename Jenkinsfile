pipeline {
    agent any
    stages {
      withEnv(['PATH+NODE=/something=/path/to/node/bin']) {
        stage('Build') { 
            steps {
                sh 'npm install -g yarn'
                sh 'yarn install'
            }
        }
      }
    }
}