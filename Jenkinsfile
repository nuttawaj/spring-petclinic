pipeline {
  agent any
  stages {
    stage('shell') {
      steps {
        sh 'pwd'
      }
    }

    stage('error') {
      steps {
        sh '''pwd
mvn clean compile
pwd'''
        sh 'pwd'
      }
    }

  }
}