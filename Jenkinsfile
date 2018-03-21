pipeline {
  agent any
  stages {
    stage('Run unit tests') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}