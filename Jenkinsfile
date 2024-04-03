pipeline {
    agent any

    stages {

        stage('git clone') {
            steps{
                branch: 'main' git 'https://github.com/KIMHEEHO/CultureRoadFinal.git'
            }
        }

        stage('Build') {
            steps {
                sh "echo 'build'"
            }

        }
    }
}
