pipeline {
  agent any
  stages {
    stage('Get Latest') {
      steps {
        git(url: 'https://github.com/RobertZhangCanada/TestAAD2.git', branch: 'main', poll: true)
      }
    }
  }
}