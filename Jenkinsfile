pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh "npm install"
               // sh "pm2 stop node"
                sh "pm2 start --name node  npm -- start"
                sh "sleep 10"
                sh "pm2 list"
            }
        }
    }
    }
