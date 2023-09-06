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
                    docker.image(dockerImage).run('-d -v D:/AUTOMATION_Pracice/Reports/report:/app/Allurerp')
                }
            }
        }
 
        stage('Build and Test') {
            steps {
                // Add build and test steps here
            }
        }
 
        stage('Cleanup') {
            steps {
                // Clean up any resources or containers if needed
            }
        }
    }
}
