#!groovy
node {	
	stage('Checkout') {
	    checkout scm
	}
	
	stage('Deploy') {
		sh 'sudo docker-compose up -d'
	}
}

	