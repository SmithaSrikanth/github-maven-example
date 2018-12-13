
pipeline {
  agent any
    stages {
       stage('CodeCheckOut') {
         steps {
            script { 
               checkout scm
               def mvnHome = tool 'maven-3'
               def javaHome = tool 'JAVA_1.8'
                  }
             }
            }
        stage('Build') {
        steps {
           script {
            sh 'java -version'
            sh 'sudo yum -y install maven'
          /*env.JAVA = "${tool 'JAVA_1.8'}"
          checkout scm
          def mvnHome = tool 'maven-3'
          def JavaHome = tool 'JAVA_1.8' */
         }
         }
         } 
        }
      }

