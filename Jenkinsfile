pipeline {
  agent any
  stages {
    stage('check env') {
      steps {
        tool 'Nodejs'
        sh 'nodejs -v'
        sh 'npm -v'
      }
    }

  }
}