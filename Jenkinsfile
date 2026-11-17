pipeline {
    agent any

    stages {
        stage('Docker compose') {
            steps {
                dir('') {
                    sh 'docker compose up -d --build'
                }
            }
        }
    }
}
