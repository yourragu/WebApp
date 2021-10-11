pipeline {
  agent any
  stages {
    stage('WebApp') {
      steps {
        sh '''cd C:\\Users\\Ramesh\\.jenkins\\workspace\\WebApp_Dev\\target
'''
        bat 'StartApp.bat'
        bat 'StopApp.bat'
      }
    }

  }
}