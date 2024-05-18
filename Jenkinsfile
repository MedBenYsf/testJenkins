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
    post {
        always {
            echo 'job run finished'
        }
        success {
            echo 'job run finished with success'
        }
        failure {
            echo 'job run finished with failure'
        }
    }
}