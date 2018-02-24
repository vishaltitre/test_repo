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
                echo 'Testing..'
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
