pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ping -c 2 localhost'
      }
    }

    stage('test') {
      steps {
        sh 'ping -c 3 localhost'
      }
    }

    stage('production') {
      steps {
        sh 'ping -c 4 localhost'
      }
    }

  }
}