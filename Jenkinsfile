pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building branch2..'
                 sh 'printenv'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing branch2..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying branch2....'
            }
        }
    }
}