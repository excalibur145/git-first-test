pipeline {
  agent any
  stages {
    stage('check-step') {
      parallel {
        stage('check-step') {
          steps {
            git(url: 'https://github.com/excalibur145/git-first-test', branch: 'main')
          }
        }

        stage('contents') {
          steps {
            sh 'ls -la'
          }
        }

      }
    }

  }
}