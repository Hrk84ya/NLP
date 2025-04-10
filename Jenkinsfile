pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
                // Example: pip install or docker build
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
                // Example: pytest or unittest
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying application..."'
                // Example: docker run, scp to server, etc.
            }
        }
    }
}
