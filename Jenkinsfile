pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Build Successful'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running Tests'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Application Deployed Successfully'
            }
        }
    }
}
