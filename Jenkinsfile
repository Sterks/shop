pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'pwd'
        archiveArtifacts(allowEmptyArchive: true, artifacts: '*')
      }
    }
  }
}