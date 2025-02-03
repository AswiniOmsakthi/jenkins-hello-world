pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Use triple quotes and the call operator (&) in PowerShell
                powershell '''
                    & "C:/Users/sarat/AppData/Local/Programs/Python/Python312/python.exe" "hello.py"
                '''
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Use Write-Output instead of echo for clarity
                powershell 'Write-Output "Running Windows tests..."'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                powershell 'Write-Output "Deploying on Windows..."'
            }
        }
    }
}
