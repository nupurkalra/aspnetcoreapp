pipeline {
    agent any

    stages {
        stage('Restore NuGet Packages') {
            steps {
                dotnet restore
            }
        }
        stage('Build') {
            steps {
                dotnet build
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
