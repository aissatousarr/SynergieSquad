pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                dir("Containers/simple-flask-app") {
                    sh 'sudo docker build -t simple-flask-app:latest .'
                }
            }
        }
}
}
