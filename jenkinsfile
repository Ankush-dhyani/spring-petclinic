pipeline {
   agent any

   stages {
      stage('Checkout') {
         steps {
            git 'https://github.com/Ankush-dhyani/spring-petclinic.git'
         }
      }
      stage('build'){
          steps {
              sh 'mvn clean package'
          }
      }
   }
}
