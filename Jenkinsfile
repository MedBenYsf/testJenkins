pipeline {
    stages {
        stage('clone') {
            steps {
                sh "rm -rf *"
                sh "git clone https://github.com/MedBenYsf/testJenkins.git"
            }
        }
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