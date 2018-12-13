pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/Kranti143/infosys.git', branch: 'Master', credentialsId: 'Kranti143')
      }
    }
  }
}