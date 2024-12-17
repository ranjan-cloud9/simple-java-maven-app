pipeline {
    agent any
    tools {
        maven 'Maven 3.9.9'
        }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        stage('Test') {
            steps {
                // Run unit tests using Maven
                sh 'mvn test'
            }
        }
    }
}