pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'whoam1'
        git(url: 'https://github.com/Millanjena1/know-blueocean', branch: 'main', poll: true)
      }
    }

  }
}