pipeline {
    agent { docker { image 'node:14-alpine' } }
    stages {
        stage('NPM VERSION') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
