pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps { echo 'Checking out code...' }
        }
        stage('Build') {
            steps { echo 'Building project...' }
        }
        stage('Test') {
            steps { echo 'Running tests...' }
        }
        stage('Package') {
            steps { echo 'Packaging application...' }
        }
    }
    post {
        success { echo 'Pipeline succeeded.' }
        failure { echo 'Pipeline failed.' }
    }
}