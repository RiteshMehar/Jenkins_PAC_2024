pipeline {
    
    agent any
    
     stages {
          stage('SCM') {
               steps {
                echo 'Hi SCM'
		git branch: 'main', url: 'https://github.com/RiteshMehar/jenkins_2024_test1.git'

            }
          }
          stage('Build') {
             steps {
                echo 'Hi Build'
            }  
          }
          stage('Test') {
               steps {
                echo 'Hi Test'
            }
          }
	  stage('QAT') {
               steps {
                echo 'Hi QAT'
            }
          }
          stage('Deploy') {
               steps {
                echo 'Hi Deploy'
            }
          }
         }
    
    
}
