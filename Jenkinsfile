pipeline {
  agent any
  stages {
    stage('ReleaseStart') {
      steps {
        powershell 'write-host "Release started"'
      }
    }
    stage('Release Completed') {
      steps {
        powershell(script: 'write-host "Release Completed"', returnStatus: true, returnStdout: true)
      }
    }
  }
}