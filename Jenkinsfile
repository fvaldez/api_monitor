pipeline {
  agent any
  stages {
    stage('Postman Test') {
      steps {
        sh '''sh \'npm install\'
sh \'npm run api-test-production\''''
      }
    }
  }
}