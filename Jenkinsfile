pipeline {
  agent any
  tools {
    nodejs 'node'
  }
  stages {
    stage('Version') {
      steps {
        bat 'npm version'
      }
    }
    // stage('Clone') {
    //   steps {
    //     git branch: 'master',
    //         url: 'https://github.com/RomanDeveloperGit/jenkins-for-frontend-example.git'
    //   }
    // }
    // stage('Install node modules') {
    //   steps {
    //     sh 'npm ci'
    //   }
    // }
    // stage('Check linter') {
    //   steps {
    //     sh 'npm run lint'
    //   }
    // }
    // stage('Unit & Integration tests') {
    //   steps {
    //     sh 'npm run test'
    //   }
    // }
    // stage('Build') {
    //   steps {
    //     sh 'npm run build'
    //   }
    // }
    // stage('Test') {
    //   steps {
    //     echo 'QA testing...'
    //   }
    // }
    // stage('Deploy') {
    //   steps {
    //     echo 'Deploying...'
    //   }
    // }
  }
}
