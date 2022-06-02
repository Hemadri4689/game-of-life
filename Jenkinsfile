pipeline {
    agent any
     tools {
         jdk 'java 8'
         maven 'maven3.3.9'
         }
    stages{
        stage ('gitclone') {
            steps {
                    checkout scm 
                }
		}
        stage ("maven build") {
            steps {
                         sh 'mvn install'
                  }
                 }
               }
          }

