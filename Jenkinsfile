pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'npm istall'
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