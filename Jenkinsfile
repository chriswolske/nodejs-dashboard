pipeline {
  agent any
  tools {nodejs "default_node"}
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
