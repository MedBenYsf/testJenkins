pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh "which npm"
                sh "/usr/bin/npm i"
            }
        }
        stage('test') {
            steps {
                sh "npm run test"
            }
        }
    }
}