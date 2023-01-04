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

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

    stage('monitor') {
      steps {
        echo 'monitoring'
      }
    }

  }
}