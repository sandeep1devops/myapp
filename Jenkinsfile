pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
         stage('--verify--') {
            steps {
                sh "mvn verify"
            }
        }
            stage('--validate--') {
            steps {
                sh "mvn validate"
            }
        }
            stage('--compile--') {
            steps {
                sh "mvn compile"
            }
        }
    }
}
