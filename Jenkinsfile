pipeline {
    agent any

    stages {
        stage('Hello from GitHub') {
            steps {
                echo 'Pipeline is running from Jenkinsfile in GitHub!'
            }
        }

        stage('Check Docker') {
            steps {
                sh 'docker --version'
            }
        }
    }
}
