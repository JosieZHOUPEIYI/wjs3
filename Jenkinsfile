pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "build"'
        echo 'execute install#################'
        npm install || exit 1
        echo 'execute install done#################'
      }
    }

    stage('test') {
      steps {
        sh 'echo "test....."'
      }
    }

  }
}