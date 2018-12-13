pipeline {
        agent any 
        stages {
          stage('checkout') {
            steps {
              checkout scm
              def mvHome = tool 'maven-3'
                         }
                 }
            stage('Build') {
            steps {
                echo 'mvn clean install'
                  }
                 }
                }
               }
