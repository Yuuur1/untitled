pipeline {
  agent any
  stages {
    stage('Functional Test') {
      parallel {
        stage('Functional Test') {
          steps {
            bat 'mvn clean test'
          }
        }

        stage('Functional test 2') {
          steps {
            bat 'mvn --version'
          }
        }

      }
    }

  }
}