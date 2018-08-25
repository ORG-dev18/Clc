pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/ORG-dev18/Clc', branch: 'master', credentialsId: 'github_by_jenkins')
      }
    }
  }
}