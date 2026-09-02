pipeline {
    agent any
    stages {

        stage('Checkout Code') {
            steps {
                git branch : 'main', url: 'https://github.com/Koushick25/jenkins_pipeline.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python3 sum.py'
            }
        }
    }
}