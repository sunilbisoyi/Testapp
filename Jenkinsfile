pipeline {
  agent any
  stages {
    stage('ReleaseStart') {
      steps {
        powershell(script: 'write-host "Test"', returnStatus: true, returnStdout: true)
      }
    }
    stage('Release Completed') {
      steps {
        powershell(script: 'write-host "Release Completed"', returnStatus: true, returnStdout: true)
      }
    }
  }
}