pipeline {
	 agent any
	 stages {
	 	stage('Upload to AWS.') {
			       steps {
			       	     sh 'echo "Uploading content with AWS creds"'
				     sh '''
				     s3Upload(pathStyleAccessEnabled: true, payloadSigningEnabled: true, file:'index.html', bucket:'static-jenkins-pipeline0')
				     }

				}
		}
	}
