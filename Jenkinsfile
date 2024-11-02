pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/marieme1807/webapps.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Insert build steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Insert test steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Insert deploy steps here
            }
        }
    }
}
