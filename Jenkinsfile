pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the .NET Application...'
                bat 'dotnet build'
            }
        }
        stage('Run Tests') {
            steps {
                echo 'Running Unit and Integration Tests...'
                bat 'dotnet test'
            }
        }
    }
}