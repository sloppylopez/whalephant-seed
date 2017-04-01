pipeline {
    agent any

    stages {
        stage('Install Deps') {
            steps {
                sh 'apt-get -y install docker-compose'
            }
        }
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