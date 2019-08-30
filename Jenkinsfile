pipeline {
  agent {
    docker {
      image 'hrss/android-builder'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'ls'
      }
    }
  }
}