pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Current Branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Build') {
            steps {
                echo "Building ${env.BRANCH_NAME}"
            }
        }

        stage('Test') {
            steps {
                echo "Testing ${env.BRANCH_NAME}"
            }
        }

        stage('Deploye') {
            steps {
                echo "Deploying ${env.BRANCH_NAME}"
            }
        }
    }
}
