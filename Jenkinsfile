@Library('sprints-library') _

pipeline {
  agent any
  
  stages {
    stage('building please') {
      steps {
        build()
      }
    }
  }
     
    stages {
    stage('testing') {
      steps {
        deployment()
      }
    }
  }    
}
