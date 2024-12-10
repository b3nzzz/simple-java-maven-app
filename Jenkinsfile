pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Command to build the Java application using Maven
                sh 'mvn clean package'
            }
        }
    }
}
