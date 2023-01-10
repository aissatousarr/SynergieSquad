pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                
                    sh 'docker build -t synergie3:latest .'
                
            }
        }
}
}
