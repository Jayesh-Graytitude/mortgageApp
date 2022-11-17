def JENKINS_WS='Jayesh'
pipeline {
	agent {label 'sandbox'}
	environment {
        ZAPPBUILD_WS = 'Patel'
    }
	stages {
		stage('Clone Application Repo') {
			steps {
				script {
					echo "The user is ${JENKINS_WS}"
					JENKINS_WS = 'Diyanshu';
				}
//				echo "Jayesh - Clone Application Repo here"
//			    echo "Current Job Build number is ${env.BUILD_NUMBER}"
//				echo "workspace directory is ${env.WORKSPACE}"
//				echo "build URL is ${env.BUILD_URL}"
//				JENKINS_WS = ${env.WORKSPACE}
//				echo "Jenkins workspace is ${JENKINS_WS}"
			}
		} 
		stage('Clone zAppbuild') {
			steps {
				echo "The user is ${JENKINS_WS}"
				echo "Jayesh - clone zAppbuild here"
			}
		}
		stage('Execute Impact Build') {
			steps {
				echo "Jayesh - Execute build here now"
//					export DBB_HOME=/usr/lpp/IBM/dbb
//				sh '''
//					export | tee
//					/usr/lpp/IBM/dbb/bin/groovyz -DBB_PERSONAL_DAEMON /u/jayesh-zappbuild-sandbox/dbb-zappbuild/sandbox/zAppbuild/build.groovy --workspace /u/jayesh-zappbuild-sandbox/Application --application mortgageApp --outDir /u/jayesh-zappbuild-sandbox/out --hlq ADCDMST.DBB --verbose mortgageApp/cobol/epsmpmt.cbl
//				'''	
			}
		}
	}
}