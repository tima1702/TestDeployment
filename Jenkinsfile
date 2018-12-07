pipeline {
  agent {
    docker {
      image 'node:carbon'
      args '-p 3001:3001'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
  }
}