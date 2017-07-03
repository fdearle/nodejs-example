pipeline {
  agent any
  stages {
    stage('Build Container') {
      steps {
        sh 'docker build -t calculator -f Dockerfile.production .'
      }
    }
  }
}