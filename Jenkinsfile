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
        stage('') {
          steps {
            echo 'first 1'
          }
        }
      }
    }
  }
}