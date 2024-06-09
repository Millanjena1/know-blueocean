pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        git(url: 'https://github.com/Millanjena1/know-blueocean', branch: 'main', poll: true)
      }
    }

    stage('stage2') {
      steps {
        echo 'MILLAN'
      }
    }

  }
}