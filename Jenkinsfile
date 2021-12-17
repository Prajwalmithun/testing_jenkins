pipeline {
    agent { any { image 'python:3.10.1-alpine' } }
    
    stages {
        
        stage('build') {
            steps {
                /*sh 'python --version'*/
                echo "We are building"
            }
        }
        stage('test') {
            steps {
                /*sh 'python --version'*/
                echo "We are testing!!"
            }
        }
        stage('Deploy') {
            steps {
                /*sh 'python --version'*/
                echo "We are deploying"
            }
        }
    }
}


/*Generic syntax

# pipeline -> Top level
# agent -> where to execute
# stages -> Where the work really happens
  - "stage and "steps" are within stages
pipeline{ 
  agent any
  
  stages{
    stage("build"){
      steps{
        
      }
  }
}
*/
