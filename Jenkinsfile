pipeline {
    agent any
triggers {
        // Poll GitHub every 1 minute for changes
        pollSCM('* * * * *')
    }
stages {
        stage('Checkout') {
            steps {
                git branch: 'dev', url: 'https://https://github.com/deepaksoam313/DevOps-Academy-Training.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                // Example build command
                //sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example test command
            }
        }
}
}
