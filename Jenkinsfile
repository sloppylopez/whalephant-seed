pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'docker build -f="whalephant-seed" .'
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