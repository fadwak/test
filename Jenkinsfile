pipeline {
  agent any
  stages {
    stage('hi team') {
      steps {
        echo 'first Hi'
      }
    }
    stage('third step') {
      steps {
        retry(count: 3) {
          sh 'echo "hi"'
        }
        
      }
    }
  }
}