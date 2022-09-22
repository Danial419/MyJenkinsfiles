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
        
        stage('Testing') {
            steps {
                sh './jenkins/scripts/test.sh
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
	    
	}
   
}
