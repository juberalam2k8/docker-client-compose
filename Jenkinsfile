pipeline {
   agent any

   stages {
      stage('Deploy') {
         steps {
            git 'https://github.com/juberalam2k8/docker-client-compose.git'
            bat 'docker-compose build'
            bat 'docker-compose up'
         }
      }
   }
}
