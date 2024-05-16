pipeline {
    agent {
        docker {
          image 'node:10.11.0-alpine'
          label 'my-nodejs-image'
        }
     }
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