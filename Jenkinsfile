pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'git@github.com:rob-thl/fictional-guacamole.git', branch: 'master')
      }
    }
  }
  environment {
    CI = 'true'
  }
}