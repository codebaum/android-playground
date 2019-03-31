pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        sh './gradlew clean assembleDebug'
      }
    }
    stage('Unit Test') {
      steps {
        sh './gradlew testDebugUnitTest'
      }
    }
  }
}