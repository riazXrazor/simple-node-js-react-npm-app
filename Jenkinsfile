pipeline {
    agent {
        docker {
            image 'node:current-alpine3.12'
            args '-p 30003000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}