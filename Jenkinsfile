pipeline {
    agent any

    stages {

        stage('github-clone') {
            steps{
                git branch:'', credentialsId: 'heeho', url : '{REPOSITORY URL}'
            }
        }

        stage('Build') {
            steps {
                sh "echo 'build'"
            }

        }
    }
}
