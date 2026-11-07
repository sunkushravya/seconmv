pipeline {
    agent any

    stages {
        stage('Hello World') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Compile') {
            steps {
                bat 'mvn compile'
            }
        }

        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}