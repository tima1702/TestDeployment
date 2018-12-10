pipeline {
  agent {
    dockerfile {
      filename '/root/TestDeployment/docker-compose-prod.yml'
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