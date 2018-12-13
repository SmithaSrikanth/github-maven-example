pipeline {
        agent any 
        stages {
          stage('checkout') {
            steps {
              checkout scm
              def mvnHome = tool 'maven-3'
                         }
                 }
            stage('Build') {
            steps {
                echo 'mvn clean install'
                  }
                 }
                }
               }
