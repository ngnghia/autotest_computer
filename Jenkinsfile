pipeline {
    agent {
        docker { image 'cont' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
