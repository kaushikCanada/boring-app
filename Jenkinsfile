pipeline {
  agent any
  stages {
    stage('Preparation') {
      parallel {
        stage('Preparation') {
          agent any
          steps {
            sh 'echo \'hello world\''
            echo 'building job'
          }
        }
        stage('networking') {
          steps {
            sleep 10
          }
        }
      }
    }
  }
}