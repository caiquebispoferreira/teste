pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hi'
            echo 'teste'
          }
        }

        stage('parallel') {
          steps {
            echo 'parale'
          }
        }

        stage('okoko') {
          steps {
            echo 'teste'
          }
        }

      }
    }

    stage('teste') {
      steps {
        echo 'teste'
      }
    }

    stage('error') {
      agent any
      steps {
        echo 'using docker'
      }
    }

  }
}