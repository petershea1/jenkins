pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'echo "Building..."'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo "Testing..."'
                sh "./gradlew build"
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo "Deploying..."'
            }
        }
    }
}
