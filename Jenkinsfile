pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Build the Maven project
                sh 'mvn clean install'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the built artifact to the deployment environment
                sh 'mvn deploy'
            }
        }
    }
}
