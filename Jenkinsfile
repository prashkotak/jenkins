pipeline {
	agent {
		label 'docker'
	}	
	
	stages {
		stage('Build') {
			steps {
				sh 'docker version'
				sh 'docker run httpd'
				
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
