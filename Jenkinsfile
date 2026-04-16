pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Run Script') {
            steps {
                sh 'cat app.py'
            }
        }

        stage('Message') {
            steps {
                sh 'echo Pipeline executed successfully'
            }
        }
    }
}
