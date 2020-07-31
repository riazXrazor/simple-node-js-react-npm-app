pipeline {
    agent {
        docker {
            image 'node6-alpine'
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