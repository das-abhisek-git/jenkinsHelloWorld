pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        build 'DeliveryBuild'
      }
    }

    stage('test') {
      steps {
        git 'https://github.com/das-abhisek-git/jenkinsHelloWorld.git'
      }
    }

  }
}