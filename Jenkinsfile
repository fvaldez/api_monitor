pipeline {
  agent any
  stages {
    stage('Postman Test') {
      steps {
        git 'https://github.com/fvaldez/api_monitor.git'
        sh 'npm run api-test-production'
      }
    }
  }
}