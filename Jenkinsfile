pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            echo 'test'
            echo '234242'
            sh 'echo "hello world"'
          }
        }

        stage('git') {
          steps {
            echo 'dusd'
          }
        }

      }
    }

  }
}