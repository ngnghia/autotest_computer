pipeline {
    agent {
        docker { image 'cont_api:goofy_goldberg' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'docker run -d -v D:/AUTOMATION_Pracice/Reports/report:/app/Allurerp cont_api'
            }
        }
    }
}
