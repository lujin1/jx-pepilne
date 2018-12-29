pipeline {
  agent {
    label 'jenkins-maven'
  }
  stages {
    stage('test') {
      steps {
        sh 'echo hello'
      }
    }
    stage('1111') {
      steps {
        echo '1111'
      }
    }
    stage('2222') {
      steps {
        build 'jx-pepilne'
      }
    }
  }
}