pipeline {
  agent none
  stages {
    stage('Read Email') {
      parallel {
        stage('Read Email') {
          steps {
            echo 'Reading Email Started'
          }
        }
        stage('Match text') {
          steps {
            echo 'Text Matched'
          }
        }
        stage('Move to folder') {
          steps {
            echo 'Moved to folder'
          }
        }
      }
    }
    stage('Download Attachment') {
      parallel {
        stage('Download Attachment') {
          steps {
            echo 'Attachment Downloaded'
          }
        }
        stage('Download Email attachment ') {
          steps {
            echo 'Email Attachment Downloaded'
          }
        }
      }
    }
    stage('Format Data') {
      parallel {
        stage('Format Data') {
          steps {
            echo 'Formatting Data'
          }
        }
        stage('OCR - PDF to TXT') {
          steps {
            echo 'Converting PDF to TXT'
          }
        }
        stage('Structure - TXT to XLS') {
          steps {
            echo 'Text structured to XLS'
          }
        }
      }
    }
  }
}