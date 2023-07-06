@Library('srints-library') _  
pipeline {
     agent any
    parameters {
        booleanParam(name:'test', defaultValue: true, description:'this paramater help you to know project name')
        choice(name: 'namespace', choices:['dev','prod','stage'], description: '' ) 
    }

    stages {
        stage('build') {
            steps {
                building()
            }
        }

       
        stage('deploy') {  
            steps {
               deploying()
            }
        }    
    }
}
