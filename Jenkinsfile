pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        sh 'git clone '
      }
    }
    stage('unit test') {
      steps {
        sh 'unit test'
      }
    }
    stage('docker build') {
      steps {
        sh 'docker build'
      }
    }
    stage('deploy to k8s') {
      steps {
        sh 'deploy to k8s'
      }
    }
  }
}