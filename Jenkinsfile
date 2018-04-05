pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        mail(subject: 'test', body: 'test', from: 'mramsey@test.fau.edu', to: 'mramsey@fau.edu')
      }
    }
  }
}