pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git branch: 'main',
            url: 'https://github.com/ddeeppak/ddeeppak.git',
            credentialsId: 'github-pat'
      }
    }

    stage('Build') {
      steps {
        echo 'Running build stage...'
        sh 'ls -la'   // replace with your actual build commands
      }
    }

    stage('Test') {
      steps {
        echo 'Running tests...'
      }
    }
  }
}
