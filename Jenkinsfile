pipeline {
  agent any
  stages {
    stage('Push Code') {
      steps {
        sshagent(['github-ssh']) {
          sh 'git push origin HEAD:master'
        }
      }
    }
  }
}
