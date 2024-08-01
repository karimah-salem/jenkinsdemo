pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building"'
                sh 'ls'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing"'
                sh 'pwd'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying"'
                sh 'touch deploy.txt'
                sh 'mv deploy.txt /tmp/'
            }
        }
    }
}
