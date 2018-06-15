pipeline {
    agent any

    stages {
        stage('Build') { 
            steps { 
		archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
            }
        }
       stage('Test') {
            echo 'Building....'
        }
	stage('Deploy') {
	    echo 'Deploying....'
        }
	       
     }
}