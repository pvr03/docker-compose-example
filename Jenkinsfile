pipeline {
agent { node { label 'dem' } }
stages {
   stage('Deployment'){
     steps {
         dir('/webapps/docker-compose-example'){
        sh 'sudo docker-compose down'
        sh 'sudo docker-compose up -d'
        }
     }
    }
}
}

