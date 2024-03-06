pipeline {
    agent none
    stages {
        stage('Run Tests') {
            parallel {
                stage('Test On Windows') {
                    steps {
                        echo "on windows"
                    }
                    post {
                        always {
                            echo "post"
                        }
                    }
                }
            }
        }
    }
}
