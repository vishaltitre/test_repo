pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh './testshell.sh'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello "$name" How are you ?'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Result') {
            steps {
                echo 'Success..'
            }
        }
    }
}
