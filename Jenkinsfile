pipeline {
    agent any
    tools {nodejs "nodejs"}
    stage('Droit') { 
            steps {
                sh 'sudo chown -R 1001230000:0 "/.npm"' 
            }
        }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
       
    }
}
