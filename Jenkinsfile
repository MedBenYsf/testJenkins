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
                retry(3)
                sh "npm run test"
            }
        }
    }
}