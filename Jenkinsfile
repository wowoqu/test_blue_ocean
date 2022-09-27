pipeline {
  agent {
    docker {
      image 'node'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('test') {
      agent {
        node {
          label 'test'
        }

      }
      steps {
        sh 'node -v'
      }
    }

  }
}