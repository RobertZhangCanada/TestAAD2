pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Pulling latest'
        git(url: 'https://github.com/RobertZhangCanada/TestAAD2.git', branch: 'master', poll: true, changelog: true)
      }
    }
  }
}