pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo "Building code using Gradle."
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo "Conducting unit tests using Selenium."
            }
        }
        stage('Code Analysis') {
            steps {
                echo "Analysing code using SonarQube."
            }
        }
        stage('Security Scan') {
            steps {
                echo "Scanning code using the Fortify plugin."
            }
            
        }
        stage('Integration Tests on Staging') {
            steps {
                echo "Running integration tests on staging environment."
            }
            
        }
        stage('Deploy to Production') {
            steps {
                echo "Deploying application to the production server."
            }    
        }
    }
}