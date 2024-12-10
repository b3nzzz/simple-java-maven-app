pipeline {
    agent any
    tools {
        maven 'Maven' // Name of the Maven installation in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
