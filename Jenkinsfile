pipeline {
    agent any

    stages {
      dir("xyz") {
        stage('Hello') {
            steps {
              echo 'Hello'
              sh "pwd"
            }
        }
      stage('World') {
            steps {
              echo 'World Stage'
              sh "pwd"
            }
        }
      }
      stage('outside') {
            steps {
              echo 'outside Stage'
              sh "pwd"
            }
        }
    }
}
