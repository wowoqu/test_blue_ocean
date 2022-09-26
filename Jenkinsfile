pipeline {
  agent {
    node {
      label 'test'
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
        sh 'npm -v'
      }
    }

  }
}