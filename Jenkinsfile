pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                powershell 'python hello.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                powershell 'echo "Running Windows tests..."'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                powershell 'echo "Deploying on Windows..."'
            }
        }
    }
}
