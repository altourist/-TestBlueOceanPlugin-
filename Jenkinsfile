pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello abedat'
      }
    }

    stage('Test Stage') {
      parallel {
        stage('Test') {
          steps {
            echo 'Running Test1'
          }
        }

        stage('Test2') {
          steps {
            echo 'Running Test2'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}