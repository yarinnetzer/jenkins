pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh ' echo Hello $hostname '
            }
        }
        stage('pwd') {
            steps {
                sh '''
                pwd
                git branch
                '''
            }
        }
    }
}
