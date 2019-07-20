pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        powershell 'write-output "Stage1"'
      }
    }
    stage('stage2') {
      steps {
        powershell 'write-output "Stage2"'
      }
    }
  }
}