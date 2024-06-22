pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            echo 'Hello'
          }
        }

        stage('') {
          steps {
            echo 'Hello'
          }
        }

      }
    }

    stage('Stage 2') {
      parallel {
        stage('Stage 2') {
          steps {
            echo 'Welcome'
          }
        }

        stage('') {
          steps {
            echo 'Welcome'
          }
        }

      }
    }

    stage('Docker Repo') {
      parallel {
        stage('Docker Repo') {
          steps {
            echo 'GitHub Connected'
          }
        }

        stage('') {
          steps {
            echo 'Docker Connected'
          }
        }

      }
    }

  }
}