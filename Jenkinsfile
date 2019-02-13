pipeline {
  agent {
    node {
      label 'AWS-Base'
    }

  }
  stages {
    stage('test_code') {
      steps {
        sh 'mvn clean verify'
      }
    }
    stage('Archive') {
      steps {
        junit '**/target/surefire-reports/*.xml'
      }
    }
  }
}