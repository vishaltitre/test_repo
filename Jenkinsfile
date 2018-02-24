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
                echo 'Hey Saloni How are you ?'
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
