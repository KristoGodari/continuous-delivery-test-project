pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git(url: 'https://github.com/KristoGodari/continuous-delivery-test-project.git', branch: 'master', changelog: true, poll: true)
      }
    }
  }
}