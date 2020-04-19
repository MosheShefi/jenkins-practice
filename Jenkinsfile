pipeline {
    agent any
    tools {nodejs "nodejs"}
    stages {
        stage('---build---') {
            steps {
                sh script:'''
                    #!/bin/bash
                    cd ./hs-ensemble-mon
                    ls
                    npm install
                    npm run ng -- build
                    '''
            }
        }
    }
}