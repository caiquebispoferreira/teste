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

    stage('') {
      agent {
        node {
          label 'docker'
        }

      }
      steps {
        echo 'using docker'
      }
    }

  }
}