
pipeline {
  agent any
    stages {
       stage('CodeCheckOut') {
         steps {
            script { 
               checkout scm
               def mvnHome = tool 'maven-3'
               def javaHome = tool 'JAVA-1.8.0'
                  }
             }
            }
        stage('Build') {
        steps {
           script {
            sh 'java -version'
            sh 'mvn clean install'
          /*env.JAVA = "${tool 'JAVA_1.8'}"
          checkout scm
          def mvnHome = tool 'maven-3'
          def JavaHome = tool 'JAVA_1.8' */
         }
         }
         } 
        }
      }

