pipeline {
  agent {
    node {
      label 'AWS-Base'
    }

  }
  stages {
    stage('test_code') {
      steps {
        sh '''uptime
df -h
pwd'''
      }
    }
  }
}