pipeline{
	agent any	
stages {
	stage ("first stage"){
		steps{
		sh '''
		echo "first stage"
		'''
	     }
	stage ('Build'){
		steps{
		sh '''
		echo 'this is build stage'
		'''
		}
	}

	}#stageendtag
}
}
