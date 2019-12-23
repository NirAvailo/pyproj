pipeline {
agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/NirAvailo/pyproj.git'
            }
        }
        stage('build') {
            steps {
                bat 'python hello.py'
            }
        
        }
    }
}
