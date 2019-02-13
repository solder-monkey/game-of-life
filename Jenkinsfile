pipeline {
  agent {
    node {
      label 'AWS-Base'
    }

  }
  stages {
    stage('test_code') {
      steps {
        build 'verify'
      }
    }
  }
}