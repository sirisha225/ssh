pipeline {
    agent any
	tools {maven 'maven'}
    stages {
        stage('Clone') {
            steps {
                git branch: 'master', credentialsId: 'bf66bb14-9a66-406d-8d73-60599d5826b2', url:'https://github.com/sirisha225/ssh.git'	
            }
        }
	     stage('Build') {
            steps {
                sh 'mvn clean package'	
            }
        }
		}
		}
