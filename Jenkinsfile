pipeline {
    agent any
 
    stages {
        stage('Checkout') {
            steps {
                // Check out your source code repository (e.g., Git)
                checkout scm
            }
        }
 
        stage('Run Docker Container') {
            steps {
                // Run an existing Docker image
                script {
                    def dockerImage = 'cont'
                    docker.image(dockerImage).run('-v /path/on/host:/path/in/container', '-e ENV_VARIABLE=value')
                }
            }
        }
    }
}
