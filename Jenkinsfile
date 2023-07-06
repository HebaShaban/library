@Library('sprints-library') _

pipeline {
  agent any
  
  stages {
    stage('Execute Groovy Script') {
      steps {
        build()
      }
    }
  }
     
    stages {
    stage('Execute Groovy Script') {
      steps {
        deployment()
      }
    }
  } 
 stages {
    stage('Execute Groovy Script') {
      steps {
        push()
      }
    }
  }    
}
