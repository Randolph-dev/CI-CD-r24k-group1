pipeline {
    agent any
    
    tools {nodejs "node"}
    
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
              echo 'Simulating tests'
              }
            }
        }
        stage('Deploy') {
            steps {
                echo "Simulate deployment to AWS"
            }
        }
    }
}