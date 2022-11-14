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
//				JENKINS_WS = ${env.WORKSPACE}
//				echo "Jenkins workspace is ${JENKINS_WS}"
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
				sh 'export | tee'
				sh 'export DBB_HOME=/usr/lpp/IBM/dbb'
				sh '/usr/lpp/IBM/dbb/bin/groovyz -DBB_PERSONAL_DAEMON /u/jayesh-zappbuild-sandbox/dbb-zappbuild/sandbox/zAppbuild/build.groovy --workspace /u/jayesh-zappbuild-sandbox/Application --application mortgageApp --outDir /u/jayesh-zappbuild-sandbox/out --hlq ADCDMST.DBB --verbose mortgageApp/cobol/epsmpmt.cbl'
			}
		}
	}
}