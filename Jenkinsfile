pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'

		sh 'python -s 'print('Test CI/CD')''

		sh 'whoami'
            }
        }
    }
}
