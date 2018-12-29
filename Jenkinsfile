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
        stage('qq') {
          steps {
            echo 'qq'
          }
        }
      }
    }
  }
}