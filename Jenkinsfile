pipeline {
    agent any 
    stages {
        stage('----clean----') { 
            steps {
                sh "mvn clean" 
            }
        }
        stage('----Test----') { 
            steps {
                sh "mvn test" 
            }
        }
        stage('----Package----') { 
            steps {
                sh "mvn package" 
            }
        }
       
    }
    
}
