pipeline {
    agent { docker { image 'python:3.13.2-alpine3.21' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('test') {
            steps {
                sh 'pip --freeze'
            }
    }
}

