pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/deepaksoam313/DevOps-Academy-Training.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
