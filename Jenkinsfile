pipeline {
  agent any
  stages {
    stage('Clone Repo') {
      steps {
        sshagent(['github-ssh-key']) {
          sh 'git clone git@github.com:username/repo.git'
        }
      }
    }
  }
}
