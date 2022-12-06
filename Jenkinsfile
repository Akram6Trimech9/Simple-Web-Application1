pipeline {
  environment {
    registry = "aishdockerid/simple-web-application"
    registryCredential = 'aishdockerid'
    dockerImage = ''
  }
  agent any
  stages {
    stage('Cloning Git') {
      steps {
        git 'https://github.com/7Aishwarya/Simple-Web-Application1.git'
      }
    }
    stage('Build') {
       steps {
         sh 'echo build '
       }
    }
    stage('Building image') {
      steps{
        script {
          echo "Buildding"
         }
      }
    }
    stage('Deploy Image') {
      steps{
         script {
          echo "deploy"
          }
        }
      }
    }
  }
}
