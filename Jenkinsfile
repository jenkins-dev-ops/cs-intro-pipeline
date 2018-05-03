pipeline {
  agent {
    label 'jdk8'
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