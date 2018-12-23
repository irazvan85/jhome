pipeline {
  agent any
  stages {
    stage('first') {
      environment {
        J_VERSION = '01'
      }
      parallel {
        stage('first') {
          steps {
            echo 'first'
          }
        }
        stage('error') {
          steps {
            echo 'first 1'
          }
        }
      }
    }
    stage('second') {
      steps {
        echo 'second'
      }
    }
  }
}