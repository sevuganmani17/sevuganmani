pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'echo "Hello world"'
      }
    }

    stage('Dev') {
      steps {
        sh 'echo "Test is done"'
      }
    }

    stage('Prod') {
      steps {
        sh 'echo "Print this message"'
      }
    }

  }
}