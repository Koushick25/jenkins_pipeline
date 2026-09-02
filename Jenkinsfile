pipeline {
    agent any
    stages {

        stage('Checkout Code') {
            steps {
                git 'YOUR_GITHUB_REPOSITORY_URL'
            }
        }

        stage('Build') {
            steps {
                sh 'python3 sum.py'
            }
        }
    }
}