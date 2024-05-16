pipeline {
    agent any
    tools {nodejs "nodejs"}
    stages {
        stage('build') {
            steps {
                sh "npm i"
            }
        }
        stage('test') {
            steps {
                sh "npm run test"
            }
        }
    }
}