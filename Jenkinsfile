pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'npm install -g nodejs-dashboard'
      }
    }

    stage('test') {
      steps {
        sh 'node test'
      }
    }

  }
}