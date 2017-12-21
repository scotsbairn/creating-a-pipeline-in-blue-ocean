pipeline {
  agent any
  stages {
    stage('Start') {
      parallel {
        stage('Start') {
          steps {
            echo 'Hello'
            echo 'There'
          }
        }
        stage('Parallel hi') {
          steps {
            echo 'Bonjour'
          }
        }
      }
    }
  }
}