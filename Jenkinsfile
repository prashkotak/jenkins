pipeline {
	agent 'docker'
	
	stages {
		stage('Build') {
			steps {
				echo 'Buiing..'
				docker version
			}
		}
		stage('Test') {
			steps {
				echo 'Testing..'
				docker run httpd
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying..'
			}
		}
		
	}
}
