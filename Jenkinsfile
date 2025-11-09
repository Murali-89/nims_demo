pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Compile') {
            steps {
                // Adjust filename if needed
                sh 'javac Lab1.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Lab1'
            }
        }
    }
}
