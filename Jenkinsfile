pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build: Compile and package code using Maven - updated build'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Unit and Integration Tests: Run automated tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis: Analyse code quality using SonarCloud'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan: Scan for vulnerabilities using Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to Staging: Deploy application to AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Integration Tests on Staging: Test the application using Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production: Deploy application to AWS EC2'
            }
        }
    }
}
