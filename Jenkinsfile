pipeline {
agent { node { label 'dem' } }
stages {
   stage('Deployment'){
     steps {
        sh 'sudo docker-compose down'
        sh 'sudo docker-compose up -d'
        }
   }

