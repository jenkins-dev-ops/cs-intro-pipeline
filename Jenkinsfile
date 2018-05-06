pipeline {
  agent any
  stages {
    stage('Publish Event') {
      steps {
        publishEvent simpleEvent('beeEvent')
      }
    }
  }
}