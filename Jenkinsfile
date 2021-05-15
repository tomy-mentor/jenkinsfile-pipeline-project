
pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                echo 'triggered with pollscm'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
