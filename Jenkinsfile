pipeline {
  agent any
  stages {
    stage('Postman Test') {
      steps {
        sh 'npm install'
        sh 'npm run api-test-production'
      }
    }
  }
}
