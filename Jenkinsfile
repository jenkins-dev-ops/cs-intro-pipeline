pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello Word!'
        sh 'java -version'
      }
    }
  }
}