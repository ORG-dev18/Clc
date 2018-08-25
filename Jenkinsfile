pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/ORG-dev18/Clc', branch: 'master', credentialsId: 'github_by_jenkins')
      }
    }
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'building my maven pro'
          }
        }
        stage('print') {
          steps {
            echo 'hello anil DevOps'
          }
        }
      }
    }
  }
}