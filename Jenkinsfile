pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'python3 hello.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Here you can add commands to run tests
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Here you can add commands to deploy your app
            }
        }
    }
}
