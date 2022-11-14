pipeline {
	agent {label 'sandbox'}
	stages {
		stage('Stage1') {
			steps {
				echo "Jayesh - stage1"
//				def buildNumber = env.BUILD_NUMBER
//				def workspace = env.WORKSPACE
//				def buildUrl = env.BUILD_URL
//			    echo "Current Job Build number is ${buildNumber}"
//				echo "workspace directory is ${workspace}"
				echo "workspace directory is ${env.WORKSPACE}"
//				echo "build URL is ${env.BUILD_URL}"
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