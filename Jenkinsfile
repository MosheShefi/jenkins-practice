pipeline {
    agent any
    tools {nodejs "nodejs"}
    stages {
        stage('---build---') {
            steps {
                sh "PATH=/sbin:/usr/sbin:/usr/bin:/usr/local/bin"
                sh "cd hs-ensemble-mon"
                sh "npm install"
                sh "ng build"
            }
        }
    }
}