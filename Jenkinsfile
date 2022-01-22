pipeline {
  agent {
    node {
      label 'slave 1'
    }

  }
  stages {
    stage('stage1') {
      steps {
        sh '''valhost=$(hostname -i)

'''
        sh 'echo \'hostname=\'$valhost'
      }
    }

  }
}