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
                withMaven(maven : 'MAVEN') {
                bat'mvn clean compile'
            }
        }
    }
}
}
