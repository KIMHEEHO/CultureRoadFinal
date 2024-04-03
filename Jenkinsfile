pipeline {
    agent any

    stages {
        stage('Ready') {
            steps {
                sh 'echo "Ready stage"'
            }
        }
        stage('github-clone') {
            steps {
                git branch: '', credentialsId:'github_token', url :'{REPOSITORY URL}'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Build stage"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploy stage"'
            }
        }
    }
}