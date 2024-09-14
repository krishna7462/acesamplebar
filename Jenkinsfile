pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/krishna7462/acesamplebar.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                // Add build steps here (e.g., compile, test, etc.)
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                // Add test steps here
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                // Add deployment steps here (e.g., deploy to AWS)
                echo 'Deploying...'
            }
        }
    }
}
