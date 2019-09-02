pipeline {
  agent {
    docker {
      image 'hrss/android-builder'
    }

  }
  stages {
    stage('error') {
      steps {
        sh '''pwd
ls
sh gradlew build'''
      }
    }
  }
}