pipeline {
    agent any
    stages {
        stage('checkout git') {
            steps {
                 docker version
            }
        }

        stage('build') {
            steps {
               sh 'docker run httpd'
	    }
        }
	}
}
