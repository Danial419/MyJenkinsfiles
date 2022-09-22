pipeline {
    agent any

    stages {
        stage('exmple') {
            steps {
                echo 'exampling...'
            }
        }
   
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
        
       
     
        stage('Maintaince') {
            steps {
                echo 'Maintaince...'
            }
        }
	    
	 stage('Release') {
            steps {
                echo 'Releasing...'
            }
        }
	    stage('build') {
                 steps {
                    sh 'npm version'
            }
        }
	    stage('test') {
                 steps {
                    sh './jenkins/scrpts/test.sh'
            }
        }
	    
	}
   
}
