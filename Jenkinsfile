pipeline {
  agent any
  stages {
    stage('Unit Test') {
      steps {
        sh 'sh \'./gradlew testDebugUnitTest\''
      }
    }
  }
}