pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'which node'
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
