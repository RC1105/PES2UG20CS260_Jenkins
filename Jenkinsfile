pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        sh 'g++ one.cpp -o new'
      }
    }
   
    stage('Test') {
      steps {
        sh './new'
      }
    }
   
    stage('Deploy') {
      steps {
        shhhhhh ''
      }
    }
  }
 
  post {
    failure {
       
          echo 'Pipeline failed'
        }
    }
   
  }
