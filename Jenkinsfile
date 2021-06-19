pipeline {
  agent any
  stages {
    stage('Fetch Code') {
      parallel {
        stage('Pull Test Code') {
          steps {
            echo 'Hello'
          }
        }

        stage('Code Status') {
          steps {
            echo 'Test Message'
          }
        }

      }
    }

    stage('Start Execution') {
      steps {
        echo 'Start Execution'
      }
    }

  }
}