pipeline {
    agent any
     tools {
         jdk 'java8'
         maven 'maven3.3.9'
         }
    stages{
        stage ('gitclone') {
            steps {
                    git "https://github.com/Hemadri4689/game-of-life.git"
                }
		}
        stage ("maven build") {
            steps {
                         sh 'mvn install'
                  }
                 }
               }
          }
