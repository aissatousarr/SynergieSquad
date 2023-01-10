pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                dir("Containers/simple-flask-app") {
                    sh 'docker build -t simple-flask-app:latest .'
                }
            }
        }
}
