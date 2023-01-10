pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                
                    sh 'docker build -t synergie3:latest .'
                
            }
            steps {

                    sh 'docker login -u kane96 -p dckr_pat_jz6zxv8cBwJRM0SD1PjySU4hsOU'

            }
            steps {

                    sh 'docker push kane96/synergie:1.0.${BUILD_NUMBER}'

            }
        }
}
}
