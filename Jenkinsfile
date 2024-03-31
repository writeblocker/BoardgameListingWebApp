pipeline {
    agent any
    
    tools { 
        jdk 'jdk17'
        maven 'maven3'
    }

    stages {        
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
        
       
    }
}
