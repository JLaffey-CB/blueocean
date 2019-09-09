pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            echo 'Hello from Blue Ocean and Jenkins'
          }
        }
        stage('StageP') {
          steps {
            sh 'ls -all'
          }
        }
      }
    }
  }
}