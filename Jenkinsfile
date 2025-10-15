pipeline {
    agent any
    stages {
        stage('Install dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Run security tests') { 
            steps {
                bat 'npm audit' 
            }
        }
        stage('Run integration test') { 
            steps {
                bat 'npm run test' 
            }
        }
    }
}