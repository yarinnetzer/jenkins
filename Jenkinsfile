pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
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
