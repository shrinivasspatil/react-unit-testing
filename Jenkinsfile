pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
         stage('Install') {
            steps {
                sh 'npm install'
            }
        }
         stage('Unit test') {
            steps {
                sh 'npm run test'
            }
        }
    }
}
