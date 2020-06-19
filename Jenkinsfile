pipeline {
  agent any
  stages {
    stage('BuildStage') {
      steps {
        echo 'Build Stage Completed'
      }
    }

    stage('TestStage') {
      steps {
        echo 'Test Stage Completed'
      }
    }

    stage('Deploy Stage') {
      steps {
        mail(subject: 'Blue Ocean Deploy Completed', body: 'Blue Ocean Deploy Completed Successfully', from: 'das.abhisek@gmail.com', to: 'abhisek.das2@cognizant.com')
      }
    }

  }
}