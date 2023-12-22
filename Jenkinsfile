pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'this is build project'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh '''date 2023
pwd
mkdir soo
cd soo
mkdir soo.html
ls
pwd'''
          }
        }

        stage('progress') {
          steps {
            echo 'progress status'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'plz deploy'
      }
    }

    stage('prod') {
      steps {
        echo 'this is prod stage'
      }
    }

    stage('deploy1') {
      steps {
        echo 'this is prod stage'
      }
    }

    stage('final') {
      steps {
        echo 'this is final stage'
      }
    }

  }
  environment {
    Mahender = 'kumar'
  }
}