pipeline {
    agent any

    stages {

        stage('github-clone') {
            steps {
                git branch: '', credentialsId:'github_token', url : '{REPOSITORY URL}'
            }
        }

        stage('Build') {
            steps {
                sh "echo 'build'"
            }

        }
    }
}
