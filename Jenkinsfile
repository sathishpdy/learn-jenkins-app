pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                    ls -la
                    npm ci
                    npm run build
                '''
            }
        }
    }
}