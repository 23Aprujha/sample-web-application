pipeline{
    agent any    
    stages{
        stage('git'){
           steps{
              git 'https://github.com/23Aprujha/sample-web-application.git'     
           }
	}	
    stage('build'){
       steps{
         sh "mvn clean install" 
       }
    }			   	
}
		  
