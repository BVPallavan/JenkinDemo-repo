pipeline {
  agent any
  stages {
    stage('Push Code') {
      steps {
        sshagent(['0f075843-a1e4-44d9-b8a4-ecb624156738']) {
          sh 'git push origin HEAD:master'
        }
      }
    }
  }
}
