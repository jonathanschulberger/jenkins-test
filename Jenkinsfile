pipeline {
    agent {
        docker { image 'node:14-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        },
        stage('Deploy') {
            steps {
                cat ./info   
            }
        }
    }
}
