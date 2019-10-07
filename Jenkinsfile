pipeline {
    agent any

    stages {
        stage('clean') {
            steps { 
                echo 'Cleaning..'
                sh './gradlew clean'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
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
    }
}
