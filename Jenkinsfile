pipeline {
    agent any

    stages {
        stage('Version') {
            steps {
                sh 'pwsh --version'
            }
        }
        stage('helloworld') {
            steps {
                sh 'pwsh hello.ps1
            }
        }     
    }
}
