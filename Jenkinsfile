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
               echo 'abc'
            }
        }
 
        stage('Cleanup') {
            steps {
                 echo 'bcd'
            }
        }
    }
}
