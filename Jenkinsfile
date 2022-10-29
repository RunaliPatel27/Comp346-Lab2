//Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent  any 
    tools {
        maven 'mvn'
    }    
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
