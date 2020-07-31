pipeline {
    agent {
        docker {
            image 'node12-alpine'
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