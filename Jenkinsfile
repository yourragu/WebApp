pipeline {
  agent any
  stages {
    stage('WebApp') {
      steps {
        bat 'mvn install'
        bat 'set JENKINS_NODE_COOKIE=dontKillMe && start /min StartApp.bat'
        bat 'StopApp.bat'
      }
    }

  }
}