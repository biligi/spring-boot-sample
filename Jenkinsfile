pipeline {
  agent any
  stages {
    stage('checkout project') {
      steps {
        checkout scm
      }
    }
    stage('') {
      steps {
        junit 'target/surefire-reports/*.xml'
      }
    }
  }
}