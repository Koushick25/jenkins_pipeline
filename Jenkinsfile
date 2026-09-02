pipeline {
    agent any
    stages {

        stage('Checkout Code') {
            steps {
                git 'https://github.com/Koushick25/jenkins_pipeline.git'
            }
        }

        stage('Build') {
            steps {
                  'python sum.py'
            }
        }
    }
}