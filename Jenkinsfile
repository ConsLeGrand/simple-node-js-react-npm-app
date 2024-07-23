pipeline {
    agent any
    environment {
        NODE_HOME = tool 'nodejs' // Assurez-vous que NodeJS est installé sur Jenkins
        PATH = "${env.NODE_HOME}/bin:${env.PATH}"
        NPM_CONFIG_CACHE = "${env.WORKSPACE}/.npm" // Utilisez un répertoire de cache local
    }

    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
