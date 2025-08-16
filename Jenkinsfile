@Library('my-shared-lib') _
pipeline {
  agent any
  options {
    skipDefaultCheckout()
  }
  stages {
    stage ('print hello') {
      steps{
        script{
          hello('Multibranch Pipeline from Main Branch')
        }
      }
    }
  }
}
