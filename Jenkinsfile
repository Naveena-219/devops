pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('slave1') {
      steps {
        sh 'echo "welcome slave1"'
      }
    }

    stage('slave 2') {
      steps {
        sh 'echo "welcome slave2"'
      }
    }

  }
}