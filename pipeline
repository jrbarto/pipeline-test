pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building with ID ${buildId}..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing with ID ${buildId}..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying with ID ${buildId}....'
            }
        }
    }
}
