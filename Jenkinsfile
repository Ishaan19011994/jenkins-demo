pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from the GitHub repository
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // Build the Maven project
                sh 'mvn clean install'
            }
        }

        stage('Deploy') {
            steps {
                // Add deployment steps if necessary
            }
        }
    }

    post {
        success {
            // Add post-build actions if necessary
        }
    }
}
