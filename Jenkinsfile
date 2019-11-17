node{
     def app
     stage('Checkout'){
       git 'https://github.com/juberalam2k8/docker-client-compose.git'
       }
     stage('Compile and Package'){
       def JAVA_HOME = tool name: 'jdk-11.0.4', type: 'jdk'
       bat docker-compose build
       bat docker-compose up
     }

}
