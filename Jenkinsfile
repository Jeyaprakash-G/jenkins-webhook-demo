pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage completed'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed'
            }
        }

        stage('Deploy (Simulation)') {
            steps {
                echo 'Deployment simulated successfully'
            }
        }
    }
}
