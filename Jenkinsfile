pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''valhost=$(hostname -i)

echo\'ipadress=\'$valhost'''
      }
    }

  }
}