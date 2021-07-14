pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo $Name'
          }
        }

        stage('Build2') {
          steps {
            sh 'echo $Build2'
          }
        }

      }
    }

    stage('Test') {
      steps {
        sh 'echo $Test'
      }
    }

  }
  environment {
    Name = 'FirstStone'
  }
}