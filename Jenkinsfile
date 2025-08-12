pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('hello') {
            steps {
                sh 'Demo.py $X_VALUE$ $Y_VALUE$'
            }
        }
    }
}
