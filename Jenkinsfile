pipeline {
    agent any

    stages {
        stage('Restore NuGet Packages') {
            steps {
                sh '/usr/local/share/dotnet/dotnet restore aspnetcoreapp.csproj'
            }
        }
        stage('Build') {
            steps {
                sh '/usr/local/share/dotnet/dotnet build'
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
