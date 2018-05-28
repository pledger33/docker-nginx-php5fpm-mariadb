pipeline {
  agent any
  stages {
    stage('Test1 ') {
      steps {
        echo 'Test n1'
      }
    }
    stage('Test2') {
      steps {
        sh 'touch /tmp/test2'
      }
    }
     stage('Checkout') {
        checkout(scm)
        sh 'git clean -xdf'
    }
  }
}
