pipeline {
  agent any
  tools {
    nodejs 'nodejs_14.16.0'
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}
