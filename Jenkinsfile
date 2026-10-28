pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Check PHP') {
            steps {
                sh 'php -v'
            }
        }

        stage('Check Composer') {
            steps {
                sh 'composer --version'
            }
        }
    }
}
