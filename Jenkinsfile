pipeline {
  agent any
  stages {
    stage('create') {
      steps {
        sh 'sh -x amr.sh'
      }
    }

    stage('build') {
      steps {
        echo 'build'
      }
    }

  }
}