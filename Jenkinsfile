pipeline {
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    app = docker.build("eslamt/node-app")

                }
            }
        }
        stage('Push Docker Image') {
            steps {
                script {
                    docker.withRegistry('https://registry.hub.docker.com', 'docker_hub_login') {                   
                        app.push("${env.BUILD_NUMBER}")
                    }
                }
            }
        }
    }   
}
