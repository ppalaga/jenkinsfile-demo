pipeline {
  agent {
      label 'maven'
  }
  stages {
      stage('oc') {
          steps {
              sh 'oc get all'
          }
      }
  }
}