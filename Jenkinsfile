pipeline {
	agent {label 'sandbox'}
	stages {
		stage('Stage1') {
			steps {
				echo "Jayesh - stage1"
			    echo "Current Job Build number is ${env.BUILD_NUMBER}"
				echo "workspace directory is ${env.WORKSPACE}"
				echo "build URL is ${env.BUILD_URL}"
			}
		} 
		stage('Stage2') {
			steps {
				echo "Jayesh - stage2"
			}
		}
		stage('Stage3') {
			steps {
				echo "Jayesh - stage3"
			}
		}
	}
}