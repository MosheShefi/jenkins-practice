pipeline {
    agent any
    tools {nodejs "nodejs"}
    stages {
        stage('---build---') {
            steps {
                sh "cd hs-ensemble-mon"
                sh "npm install"
                sh "npm run ng -- build"
            }
        }
    }
}