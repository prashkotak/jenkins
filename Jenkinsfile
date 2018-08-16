pipeline {
	agent {
		label 'docker'
	}	
	
	stages {
		stage('Build') {
			steps {
				sh 'docker version'
				
			}
		}
		stage('Test') {
			steps {
				echo 'Testing..'
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying..'
			}
		}
		
	}
}	
