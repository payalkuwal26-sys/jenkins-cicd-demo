pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the website...'
            }
        }

        stage('Test') {
            steps {
                bat 'if exist index.html (echo Test Passed) else (exit 1)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the website...'
            }
        }

    }
}
