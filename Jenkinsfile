pipeline {
  agent any
  stages {
    stage('Push Code') {
      steps {
        sshagent(['git-hub-ssh']) {
          sh 'git push origin HEAD:master'
        }
      }
    }
  }
}
