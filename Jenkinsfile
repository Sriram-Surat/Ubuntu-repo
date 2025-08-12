pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat '"C:\\Windows\\System32\\cmd.exe" /c python --version'
            }
        }
        stage('hello') {
            steps {
                bat '"C:\\Windows\\System32\\cmd.exe" /c python Demo.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}