pipeline {
    agent any
    tools {nodejs "nodejs"}
    stages {
        stage('---echo path---') {
            steps {
                sh "echo $PATH"
            }
        }
        stage('---build---') {
            steps {
                sh "cd hs-ensemble-mon"
                sh "npm install"
                sh "PATH"
                sh "npm run ng -- build"
            }
        }
    }
}