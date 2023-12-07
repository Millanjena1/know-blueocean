pipeline {
  agent any
  stages {
    stage('checkout the code') {
      steps {
        git(url: 'https://github.com/Millanjena1/know-blueocean.git', branch: 'main')
      }
    }

    stage('stage2') {
      parallel {
        stage('stage2') {
          steps {
            echo 'print'
          }
        }

        stage('stage 2.1') {
          steps {
            sh 'whoami'
          }
        }

      }
    }

    stage('stage3') {
      steps {
        sleep 5
      }
    }

  }
  environment {
    env = 'prd'
  }
}