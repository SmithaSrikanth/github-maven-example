pipeline {
        agent any 
        stages {
          stage('checkout') {
            steps {
              checkout scm
              def mvnHome = tool 'maven-3'
              def javaHome = tool 'JAVA-1.8.0'
                  }
                 }
            stage('Build') {
            steps {
                sh 'mvn clean install'
                  }
                 }
                }
               }
