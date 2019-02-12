pipeline {
  agent {
    node {
      label 'AWS-Slave'
    }

  }
  stages {
    stage('test_code') {
      steps {
        sh 'uptime'
      }
    }
  }
}