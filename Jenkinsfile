pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python hello.py'
      }
    }
    stage('maven build') {
      steps {
        sh 'maven clean package'
      }
    }  
  }
}
