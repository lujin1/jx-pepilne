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
        stage('test2') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('1') {
      steps {
        echo 'lujin'
      }
    }
    stage('2') {
      steps {
        sh 'echo "2222"'
      }
    }
    stage('s') {
      steps {
        sleep 2
      }
    }
    stage('') {
      environment {
        a = 'aaaa'
      }
      steps {
        sh 'echo $a'
      }
    }
  }
}