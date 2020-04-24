pipeline {
    agent any
    tools {
        maven 'Maven 3.3.9'
        jdk 'jdk8'
    }
   stages {
      stage('Testes de API') {
         steps {
            bat 'mvn clean package'
         }
      }
   }
}