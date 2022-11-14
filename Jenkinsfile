pipeline {
	agent {label 'sandbox'}
	environment {
        JENKINS_WS = ''
        ZAPPBUILD_WS = ''
    }
	stages {
		stage('Clone Application Repo') {
			steps {
				echo "Jayesh - Clone Application Repo here"
//			    echo "Current Job Build number is ${env.BUILD_NUMBER}"
//				echo "workspace directory is ${env.WORKSPACE}"
//				echo "build URL is ${env.BUILD_URL}"
				JENKINS_WS = ${env.WORKSPACE}
				echo "Jenkins workspace is ${JENKINS_WS}"
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