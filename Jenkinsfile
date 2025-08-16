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
          hello('Multibranch Pipeline from helm_Argo Branch')
        }
      }
    }
  }
}
