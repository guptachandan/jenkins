pipeline {
  agent any
  stages {
    stage('pre-build') {
      parallel {
        stage('pre-build') {
          steps {
            echo 'pre-build'
          }
        }

        stage('parallel') {
          steps {
            echo 'parallal'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'build'
      }
    }

  }
}