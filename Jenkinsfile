pipeline {
    agent any
    stages {
        stage('build') {
            agent {
                docker {
                    image 'python:alpine'
                }
            }
            steps {
                sh 'python --version'
            }
        }
    }
}
