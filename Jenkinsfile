pipeline {
  agent any
  stages {
    stage('WebApp') {
      steps {
        bat 'StartApp.bat'
        bat 'StopApp.bat'
        sh '''cd C:\\Users\\Ramesh\\.jenkins\\workspace\\WebApp_Dev\\target
'''
      }
    }

  }
}