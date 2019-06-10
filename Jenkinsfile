pipeline {
  agent any
  stages {
    stage('Email Activity') {
      parallel {
        stage('Read Email Subject') {
          steps {
            echo 'ok'
            echo 'read'
          }
        }
        stage('Download PDF') {
          steps {
            sleep 1
            sleep 1
          }
        }
      }
    }
    stage('OCR Activity') {
      parallel {
        stage('OCR Activity') {
          steps {
            echo 'lol'
          }
        }
        stage('Extract Data From PDF') {
          steps {
            echo 'lol'
            echo ' are you kidding me'
          }
        }
        stage('Add fields to CSV') {
          steps {
            echo 'haha'
          }
        }
      }
    }
    stage('CRM Activity') {
      parallel {
        stage('CRM Activity') {
          steps {
            sleep 1
          }
        }
        stage('Login CRM') {
          steps {
            sleep 1
          }
        }
        stage('Insert Fields from Excel') {
          steps {
            sleep 1
          }
        }
        stage('Upload PDF') {
          steps {
            echo 'd'
          }
        }
        stage('Submit request') {
          steps {
            echo 'l'
          }
        }
      }
    }
    stage('Reply back to sender') {
      parallel {
        stage('Reply back to sender') {
          steps {
            sleep 1
          }
        }
        stage('Send reply ') {
          steps {
            echo 'lol'
          }
        }
      }
    }
    stage('finish') {
      steps {
        sleep 1
      }
    }
  }
}