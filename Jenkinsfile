pipeline {
    agent { docker { image 'python:alpine' } }
    stages {
        stage('run') {
            steps {
                echo 'clarusway_Way to Reinvent Yourself'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
