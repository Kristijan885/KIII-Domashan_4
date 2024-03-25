pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'This is a message printing'
      }
    }

    stage('End') {
      steps {
        error 'This is an error'
      }
    }

  }
}