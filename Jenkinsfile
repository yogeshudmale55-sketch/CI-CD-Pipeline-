pipeline {
    agent any

   

    stages {
        stage('Install') {
            steps {
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Skipping tests - no test script found'
            }
        }
        stage('Build') {
            steps {
                bat 'npm run build'
            }
        }
        stage('Deploy') {
            steps {

                echo "Deploying"
                
            }
        }
    }
}