pipeline {
    agent any 
    stages {
        stage('----clean----') { 
            steps {
                //bat "mvn clean" 
                if (isUnix()) {
                    sh "mvn clean"
                }
                else {
                    bat "mvn clean"
                }

            }
        }
        stage('----Test----') { 
            steps {
                //bat "mvn test" 
                if (isUnix()) {
                    sh "mvn clean"
                }
                else {
                    bat "mvn clean"
                }
            }
        }
        stage('----Package----') { 
            steps {
                //bat "mvn package" 
                if (isUnix()) {
                    sh "mvn clean"
                }
                else {
                    bat "mvn clean"
                }
            }
        }
       
    }
    
}
