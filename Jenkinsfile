pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh ' echo Hello $USER '
            }
        }
        stage('pwd') {
            steps {
                sh '''
                pwd
                cd jenkins.git
                git branch
                '''
            }
        }
    }
}
