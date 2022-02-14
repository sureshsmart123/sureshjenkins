pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
            steps {
               echo "welcome step"
                sh 'node --version'
            }
        }
        stage('Test') {
            steps {
               echo "welcome step"
            }
        }
        stage('Deploy') {
            steps {
               echo "Deploy"
            }
        }
    }
}
