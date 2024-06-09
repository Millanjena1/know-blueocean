pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            git(url: 'https://github.com/Millanjena1/know-blueocean', branch: 'main', poll: true)
          }
        }

        stage('stage3') {
          steps {
            emailext(subject: 'rewr', body: 'werer', attachmentsPattern: 'erwr', attachLog: true, to: 'millan.jena0107@gmail.com', from: 'smtp.gmail.com')
          }
        }

      }
    }

    stage('stage2') {
      steps {
        echo 'MILLAN'
      }
    }

  }
}