pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                echo "Pulling code from GitHub ......"
            }
        }

        stage('Build') {
            steps {
                echo "Building Package from Code ......"
            }
        }

        stage('Test') {
            steps {
                echo "Testing Package ......"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying Application ......"
            }
        }
    }
}
