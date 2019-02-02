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
      parallel {
        stage('1111') {
          steps {
            echo '1111'
            sleep 60
          }
        }
        stage('2222') {
          steps {
            echo 'qeqw'
            sleep 45
          }
        }
      }
    }
    stage('665') {
      steps {
        sh 'echo $name'
      }
    }
  }
  environment {
    name = 'LUJIN'
  }
}