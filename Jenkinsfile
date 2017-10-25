pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            sleep 1
          }
        }
        stage('Stage 2') {
          steps {
            sleep 1
          }
        }
      }
    }
  }
}