pipeline {
  agent any
  stages {
    stage('Build Docker Image') {
      steps {
        sh 'docker build -t my-add-script-image:latest .'
      }
    }
  }
}
