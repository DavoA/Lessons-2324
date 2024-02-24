pipeline {
    agent {
        docker { image 'node:20.11.1-alpine3.19' }
    }
    stages {
        stage('Test2') {
            steps {
                sh 'node --version'
            }
        }
    }
}
