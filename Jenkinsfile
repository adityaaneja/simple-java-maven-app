pipeline {
    agent {label 'maven-agent'}
    
    
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Once Again..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Again....'
            }
        }
    }
}
