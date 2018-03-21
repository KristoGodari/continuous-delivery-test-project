pipeline {
  agent any
  stages {
    stage('Run unit tests') {
      steps {
        sh 'command || true'
      }
    }
    stage('Run integration Tests') {
      steps {
        sh 'command || true'
      }
    }
    stage('deploy on Server') {
      steps {
        sh 'command || true'
      }
    }
    stage('Run black-box stests') {
      parallel {
        stage('Run black-box stests') {
          steps {
            sh 'command || true'
          }
        }
        stage('Run Performance tests') {
          steps {
            sh 'command || true'
          }
        }
      }
    }
    stage('Destroy temp server') {
      steps {
        sh 'command || true'
      }
    }
    stage('Deploy on Uat') {
      steps {
        sh 'command || true'
      }
    }
  }
}