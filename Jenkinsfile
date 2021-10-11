pipeline {
  agent any
  stages {
    stage('WebApp') {
      steps {
        bat 'mvn install'
        bat 'StartApp.bat'
        bat 'StopApp.bat'
      }
    }

  }
}