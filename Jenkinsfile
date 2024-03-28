pipeline {
    agent { docker { image 'node:16.20.2-alpine3.18' } }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}