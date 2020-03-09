pipeline {
  agent {
    docker {
      image 'node:6-alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'nam install'
      }
    }

  }
}