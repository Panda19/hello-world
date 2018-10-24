pipeline {
  agent any
  
  options {
    buildDiscarder(logRotator(numToKeepStr: '2'))
  }
  stages {
    stage ('build') {
       steps {
         sh 'ant -v'
         sh 'du -sh'
       }
      }
}
}
