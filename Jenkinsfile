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
    stage('Check file') {
      steps {
        fileExists 'DDdocker-compose.yml'
      }
    }
    stage('Fin') {
      steps {
        echo 'FIN'
      }
    }
  }
}
