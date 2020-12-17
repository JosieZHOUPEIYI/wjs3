pipeline {
  agent {
    node {
      label 'build'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'echo "build"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "test....."'
      }
    }

  }
}