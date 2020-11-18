pipeline {
  agent {
    docker {
      image 'node:12'
      args '--network jenkins_mynet'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'cd ./example-react; npm install'
      }
    }

  }
}