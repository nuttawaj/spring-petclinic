pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Test'
        git(url: 'https://github.com/nuttawaj/spring-petclinic', branch: 'master')
      }
    }

  }
}