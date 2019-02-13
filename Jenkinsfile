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
        junit '**/target/surefire-reports/*.xml'
      }
    }
  }
}