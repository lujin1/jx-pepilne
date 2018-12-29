pipeline {
  agent {
    label 'jenkins-maven'
  }
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'echo hello'
          }
        }
        stage('1') {
          agent any
          steps {
            sh 'echo "lujin"'
          }
        }
      }
    }
  }
}