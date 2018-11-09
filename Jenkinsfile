// Powered by Infostretch 

timestamps {

node () {

	stage ('AddressBook_COMPILE_CODE - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '3cfcc284-5fb2-46c1-899b-f01e28ca83b5', url: 'https://github.com/DeepakVpatil/addressbook.git']]]) 
	}
	stage ('AddressBook_COMPILE_CODE - Build') {
 			// Shell build step
sh """ 
 
 """ 
	}
}
}