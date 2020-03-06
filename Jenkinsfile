pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        nodejs('nodejs') {
          sh 'npm install'
        }

      }
    }

    stage('test') {
      steps {
        sh 'echo "what is testing"'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "deploying"'
      }
    }

  }
}