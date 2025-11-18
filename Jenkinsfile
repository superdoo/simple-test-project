pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning the repository...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Running Python script...'
                sh 'python3 app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'This is where tests would run (optional)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'This is where deployment would happen (optional)'
            }
        }
    }
}
