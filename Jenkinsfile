pipeline {
    agent any
    stages {
        stage('Install dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Test') { 
            steps {
                bat 'npm run test' 
            }
        }
    }
}