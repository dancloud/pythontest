pipeline {
  agent { label 'kubeagent' }
  stages {
    stage('Build') {
      agent any
      steps {
        sh 'python app.py'
      }
    }

  }
}