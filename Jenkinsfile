pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -thrall && pwd && docker-compose up --build'
            }
        }
        stage('Test'){
            steps {
                sh 'echo "NO testing yet"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "deploying"'
            }
        }
    }
}