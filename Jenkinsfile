pipeline {
    agent any

    stages {
        stage('Clone repository') {
            steps {
                git 'https://github.com/fapathe/test.git'
            }
        }
        stage('Print Hello World') {
            steps {
                script {
                    def content = readFile 'hello-world.txt'
                    echo content
                }
            }
        }
    }
}
