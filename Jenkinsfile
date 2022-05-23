pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage ('Compile ')
{
steps
 {
bat 'mvn compile'
}
}
        stage('Test') {
            steps {
                echo 'Testing..'
                bat 'mvn test'
        }
        }
        
        stage('packaging') {
            steps {
                echo 'Testing..'
                bat 'mvn package'
            
        }
        }
        }
    } 
