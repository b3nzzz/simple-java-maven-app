pipeline {
    agent any
    tools {
        maven 'Maven' // Use the Maven configuration name from Jenkins Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                // Build the Java application using Maven
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                // Run unit tests using Maven
                sh 'mvn test'
            }
        }
    }
}
