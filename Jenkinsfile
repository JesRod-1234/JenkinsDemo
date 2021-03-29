pipeline {
    agent any
    tools {
        maven 'Maven 3.6.3'
    }

    stages {
        stage('build') {
            steps {
                echo 'Hello world'
                sh 'java --version'
                sh 'mvn clean compile'

            }

        }
        stage('Test'){
            steps{
                sh 'mvn test'
            }
        }
    }
}