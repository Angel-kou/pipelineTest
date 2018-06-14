// Declarative //
pipeline {
    agent any
    environment { 
        CC = 'clang'
    }
    stages {
        stage('Example') {
            environment { 
                DEBUG_FLAGS = '-g'
            }
            steps {
                sh 'printenv'
	        echo 'Deploying....'
		echo "当前BuildId: ${env.BUILD_ID}"
		echo "当前Job: ${env.JOB_NAME}"
		echo "当前URL: ${env.JENKINS_URL}"
            }
        }
    }
}
