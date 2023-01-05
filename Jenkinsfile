pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh ' myusr=`git config -l | grep user.name | awk -F '[=]' '{print $2}'`
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
