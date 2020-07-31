pipeline {
    agent {
        docker {
            image 'node:latest'
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