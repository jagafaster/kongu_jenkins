pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/jagafaster/simple-node-app.git'
            }
        }

        stage('Install') {
            steps {
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                sh 'npm test'
            }
        }

    }
}
