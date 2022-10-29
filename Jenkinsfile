//Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent  any 
    tools { 
        maven 'MAVEN' 
         
    }  
    stages {
        stage('build') {
            steps {
                withMaven(maven : 'apache-maven-3.6.1') {
                bat'mvn clean package'
            }
        }
    }
}
}
