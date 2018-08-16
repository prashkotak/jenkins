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
                docker run httpd
				
            }
        }
}
