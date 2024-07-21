pipeline {
  agent any
  stages {
    stage('shell') {
      steps {
        sh 'pwd'
      }
    }

    stage('') {
      steps {
        sh '''pwd
./mvnw clean compile
pwd'''
        sh 'pwd'
      }
    }

  }
}