pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dir(path: '/var/jenkins_home/workspace/spring-petclinic2_master') {
          sh './mvnw clean compile'
        }

      }
    }

  }
}