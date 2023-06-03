pipeline {
  agent any
  tools {
    nodejs '20.2.0'
  }
  stages {
    stage('Install node modules') {
      steps {
        bat 'npm ci'
      }
    }
    stage('Check linter') {
      steps {
        bat 'npm run lint'
      }
    }
    stage('Unit & Integration tests') {
      steps {
        bat 'npm run test'
      }
    }
    stage('Build') {
      steps {
        bat 'npm run build'
      }
    }
    stage('Test') {
      steps {
        echo 'QA testing...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }
  }
}
