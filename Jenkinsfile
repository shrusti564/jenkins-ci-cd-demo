pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning repository...'
                echo 'Source code fetched successfully!'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                echo 'Compiling source files...'
                echo 'Build completed successfully!'
            }
        }

        stage('Test') {
            steps {
                echo 'Running unit tests...'
                echo 'Running integration tests...'
                echo 'All tests passed!'
            }
        }

        stage('Code Quality Check') {
            steps {
                echo 'Analyzing code quality...'
                echo 'No critical issues found!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application to server...'
                echo 'Application deployed successfully!'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}