pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'fff'
          }
        }

        stage('tezfff') {
          steps {
            echo 'tezfff'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'build'
        echo 'dfggg'
      }
    }

  }
}