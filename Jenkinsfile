pipeline {
    agent any
    tools {nodejs "nodejs"}
    
    stages {
        stage('Droit') { 
            steps {
                sh 'sudo chown -R 1001230000:0 "/.npm"' 
            }
        }
        
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
       
    }
}
