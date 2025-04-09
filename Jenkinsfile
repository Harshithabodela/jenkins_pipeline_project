pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Add build commands here (e.g., npm install, mvn clean install)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here (e.g., npm test, mvn test)
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add deploy commands here (e.g., Docker build & push, kubectl apply)
            }
        }
    }
}
