pipeline {
    agent any
    tools {
        maven 'Maven 3.9.9'
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}