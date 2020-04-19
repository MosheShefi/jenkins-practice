pipeline {
    agent any
    stages {
        stage('---build---') {
            steps {
                sh "export PATH=/sbin:/usr/sbin:/usr/bin:/usr/local/bin"
                sh "cd hs-ensemble-mon"
                sh "npm install"
                sh "ng build"
            }
        }
    }
}