pipeline {
    agent any

    stages {
        stage('Restore NuGet Packages') {
            steps {
                sh 'dotnet restore aspnetcoreapp.csproj'
            }
        }
        stage('Build') {
            steps {
                sh 'dotnet build'
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
