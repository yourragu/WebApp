pipeline {
  agent any
  stages {
    stage('WebApp') {
      steps {
        bat 'StartApp.bat'
        bat 'StopApp.bat'
      }
    }

  }
}