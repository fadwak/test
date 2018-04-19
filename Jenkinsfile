pipeline {
  agent any
  stages {
    stage('hi team') {
      steps {
        echo 'first Hi'
      }
    }
    stage('email test') {
      steps {
        mail(subject: 'test send mail', body: 'first email', from: 'fadwa', to: 'fadwak@gmail.com')
      }
    }
  }
}