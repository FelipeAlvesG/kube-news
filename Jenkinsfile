

pipeline {
    agent any

    stages {

        stage('Build Docker Image'){
            steps{
                script{
                    dockerapp = docker.build("felipealves26/kube-news:${env.BUILD_ID}", '-f ./src/Dockerfile ./src')
                }
            }
        }

    }
}