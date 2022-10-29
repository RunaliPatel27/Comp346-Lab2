//Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent  any 
    tools { 
        maven 'MAVEN' 
        jdk 'jdk8' 
    }  
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
