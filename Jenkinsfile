pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "building application" '
                bat 'set'
            }
        }
        stage('Test') {
            steps {
                bat 'echo "running tests" '
                bat 'echo "tests passed" '
            }
        }
        stage('Test') {
            steps {
                bat 'echo "delivering application" '
            }
        }
    }
}
