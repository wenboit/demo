pipeline {
	agent any
	
	tools {
		maven 'MAVEN_3.5.4'
	}

	stages {
		stage('Build'){
			steps {
				sh "mvn clean package spring-boot:repackage"
				sh "printenv"
			}
		}
	}
}
