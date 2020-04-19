pipeline {
    agent any
    tools {nodejs "nodejs"}
    stages {
        stage('---echo path---') {
            steps {
                sh "echo $PATH"
            }
        }
        stage('---change directory---') {
            steps {
                sh "cd hs-ensemble-mon"
                sh "ls"
            }
        }
        stage('---build') {
            steps {
                sh "npm install"
                sh "npm run ng -- build"
            }
        }
    }
}