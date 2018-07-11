pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        node {
          label 'node agent'
        }

      }
      steps {
        sh 'npm install'
      }
    }
  }
}