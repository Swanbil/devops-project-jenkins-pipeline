pipeline {
  environment {
    registry = "swaninho/node-web-app"
    registryCredential = 'docker-hub-credentials'
    dockerImage = ''
  }
  agent any
  tools {nodejs "NodeJs"}
  stages {
    stage('Install dependencies of the app') {
      steps {
        sh 'echo hello'
        
      }
    }
  }
}