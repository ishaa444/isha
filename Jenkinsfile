pipeline {
  agent any

  stages {
    stage(' Build') {
    steps {
      echo 'Building...'
    }
  }
    stage('Test') {
      steps {
        sh 'java --version'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }
  }
}
