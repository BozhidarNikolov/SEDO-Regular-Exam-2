pipeline {
    agent any
    stages {
        stage('Build & Test') {
            steps {
                sh 'dotnet restore'
                sh 'dotnet build'
                sh 'dotnet test'
            }
        }
    }
}
