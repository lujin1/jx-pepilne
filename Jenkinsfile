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
    stage('665') {
      steps {
        sh 'echo $name'
      }
    }
    stage('job') {
      steps {
        build 'ptest'
      }
    }
  }
  environment {
    name = 'LUJIN'
  }
}