pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // This step checks out the code from your SCM
                checkout scm
            }
        }

        stage('Build & Test') {
            steps {
                // Your build and test steps go here
                echo 'Building and testing...'
            }
        }

        stage('Run') {
            steps {
                // Your build and test steps go here
                node index.js
            }
        }

    }
}
