pipeline {
	agent any
	
	stages {
		stage('Build') {
			steps {
				echo 'Buiing..'
				docker run httpd
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
