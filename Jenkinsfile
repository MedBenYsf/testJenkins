pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh "/usr/bin/npm i"
            }
        }
        stage('test') {
            steps {
                sh "/usr/bin/npm run test"
            }
        }
    }
}