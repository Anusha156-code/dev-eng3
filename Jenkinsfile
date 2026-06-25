pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo Building project...'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running tests..'
            }
        }

        stage('Push') {
            steps {
                sh 'echo Push to registry'
            }
        }
    }
}
