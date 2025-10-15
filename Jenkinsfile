pipeline {
  agent any
  stages {
    stage('Clone Repo') {
      steps {
        sshagent(['0f075843-a1e4-44d9-b8a4-ecb624156738']) {
          sh 'git clone git@github.com:BVPallavan/JenkinDemo-repo.git'
        }
      }
    }
  }
}
