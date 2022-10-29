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
                sh 'mvn -Dmaven.test.failure.ignore=true install'
            }
        }
    }
}
