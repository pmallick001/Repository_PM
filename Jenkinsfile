pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'echo "hello and welcome"'
      }
    }

    stage('Dev') {
      steps {
        echo 'development environment'
      }
    }

    stage('Prod') {
      steps {
        echo 'prod environment'
      }
    }

  }
}