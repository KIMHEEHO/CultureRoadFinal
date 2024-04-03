pipeline {
    agent any

    stages {

        stage('git clone') {
            steps{
                git 'https://github.com/KIMHEEHO/CultureRoadFinal.git'
            }
        }

        stage('Build') {
            steps {
                sh "echo 'build'"
            }

        }
    }
}
