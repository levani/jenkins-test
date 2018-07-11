pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'npm install'
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