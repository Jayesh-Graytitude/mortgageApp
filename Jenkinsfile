pipeline {
	agent {label 'sandbox'}
	stages {
		stage('Clone Application Repo') {
			steps {
				echo "Jayesh - stage1"
			    echo "Current Job Build number is ${env.BUILD_NUMBER}"
				echo "workspace directory is ${env.WORKSPACE}"
				echo "build URL is ${env.BUILD_URL}"
			}
		} 
		stage('Clone zAppbuild') {
			steps {
				echo "Jayesh - clone zAppbuild here"
			}
		}
		stage('Execute Impact Build') {
			steps {
				echo "Jayesh - Execute build here"
			}
		}
	}
}