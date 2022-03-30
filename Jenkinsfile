pipeline {
    agent any 
    stages {
	    
        stage('checkout') {
 
            steps {
   sh 'git clone https://github.com/mjgoutham/hello-world-war.git'
            }
        }
		        stage('build') {
 
            steps {
  sh 'mvn clean package'
            }
        }
          stage('build') {
 
            steps {
  sh 'mvn clean package'
            }
        }
	stage('Deploy') {
 
            steps {
  sh 'cp /home/ubuntu/hello-world-war/target/hello-world-war-1.0.0.war /opt/apache-tomcat-10.0.18/webapps'
            }
        }
    }
}
