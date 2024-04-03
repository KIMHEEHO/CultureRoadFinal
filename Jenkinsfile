pipeline {
    agent any

    stages {

        stage('git clone') {
            steps{
                git 'https://github.com/KIMHEEHO/CultureRoadFinal.git'
            }
        }
        stage('checkout') {
            steps {
                checkout(branch: 'main')
            }
        }

        stage('Build') {
            steps {
                sh "echo 'build'"
            }

        }
    }
}
