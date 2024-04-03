pipeline {
    agent any

    stages {

        stage('github-clone') {
            steps{
                git branch:'', credentialsId: 'heeho', url : 'https://github.com/KIMHEEHO/CultureRoadFinal.git'
            }
        }

        stage('Build') {
            steps {
                sh "echo 'build'"
            }

        }
    }
}
