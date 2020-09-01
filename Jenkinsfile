pipeline{
 agent any
 stages {
 	stage ('Build'){
 		steps {
 			
 				bat 'mvn clean install'
 		}
 	}
	
	stage ('Test'){
 		steps {
 			
 				bat 'mvn clean install'
 		}
 	}
 	
 	stage ('Deploy'){
 		steps {
 			
 				bat 'mvn clean package deploy -Dusername=max360-mule -Dpassword=@@Gaga356@@ -Denvironment=Sandbox -Dworkers=1 -Dworker.type=Micro -Dapplication.name=mulesoft-cicd-sample-app -Dmule.version=4.3.0 -DmuleDeploy'
 			}
 		}
 	}
 }