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
                cd /var/lib/jenkins/workspace/pipe1/
                git branch
                '''
            }
        }
    }
}
