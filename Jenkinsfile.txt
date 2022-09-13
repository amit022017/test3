pipeline {
    agent any
    stages {
        stage('Set-up'){
            Steps {sh 'echo "hello" > hello.txt' }
        }
        stage('List files'){
            Steps {sh 'ls -la'}
        }
    }
}