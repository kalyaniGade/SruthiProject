pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'gradle clean build'
      }
    }
    stage('test') {
      steps {
        bat 'gradle clean test'
      }
    }
  }
}