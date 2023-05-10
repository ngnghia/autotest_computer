pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo "build done ..."
                bat 'start cmd.exe /c D:'
                bat 'script.bat'
            }
        }
    }
}