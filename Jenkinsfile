pipeline {
  agent any
  stages {
    stage('test_code') {
      steps {
        sh 'mvn clean verify'
      }
    }
  }
}