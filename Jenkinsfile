pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh ' myusr=git config -l | grep user.name
                sh ' echo "Hello $myusr" '
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
