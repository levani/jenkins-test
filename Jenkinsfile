pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
    stage('test') {
      steps {
        echo 'test'
      }
    }
  }
  tools {
    nodejs 'nodejs'
  }
}