pipeline {
  agent none
  stages {
    stage('finish') {
      parallel {
        stage('finish') {
          steps {
            sleep 1
          }
        }
        stage('test') {
          steps {
            echo 'hello'
          }
        }
      }
    }
  }
}