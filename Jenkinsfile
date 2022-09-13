pipeline {
    agent any
    stages {
        stage('Set-up') {
            steps {
                sh 'echo "hello" > hello.txt'
            }
        }
        stage('List files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}