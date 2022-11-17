def JENKINS_WS='Jayesh'
pipeline {
	agent {label 'sandbox'}
//	agent {label 'built-in'}
	environment {
        ZAPPBUILD_WS = 'Patel'
    }
	stages {
		stage('Clone Application Repo') {
			steps {
				script {
					readProp = readProperties file: 'readProp.properties'
				}
				echo "First name is ${readProp['first_name']}"
				echo "Last name is ${readProp['last_name']}"
			}
		} 
		stage('Clone zAppbuild') {
			steps {
				script {
					echo "The user is ${JENKINS_WS}"
					JENKINS_WS = 'Diyanshu';
				}
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