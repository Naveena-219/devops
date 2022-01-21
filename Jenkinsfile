pipeline {
  agent any
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