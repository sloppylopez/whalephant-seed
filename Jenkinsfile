pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'docker-compose up --build'
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