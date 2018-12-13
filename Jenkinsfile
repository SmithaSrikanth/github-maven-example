pipeline {
        stages {
          stage('checkout') {
            steps {
              checkout scm
              def mvnHome = tool 'maven-3'
              def javeHome = tool ' JAVA-1.8'
                  }
                 }
            stage('Build') {
            steps {
                sh 'mvn clean install'
                  }
                 }
                }
               }
               
