/* Requires the Docker Pipeline plugin */
pipeline {
    agent { any { image 'python:3.12.0-alpine3.18' } }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
