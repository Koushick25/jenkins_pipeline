pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Changed from python3 to python
                bat 'python sum.py'
            }
        }
    }
}
