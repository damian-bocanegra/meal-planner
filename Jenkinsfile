pipeline {
    agent any
    withEnv(['PATH+NODE=/something=/path/to/node/bin']) {
        stages {
            stage('Build') { 
                steps {
                    sh 'npm install -g yarn'
                    sh 'yarn install'
                }
            }
        }
    }
}