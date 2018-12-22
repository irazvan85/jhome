pipeline {
  agent any
  stages {
    stage('first') {
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
        echo 's1'
      }
    }
  }
}