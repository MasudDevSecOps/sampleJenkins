pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac src/HelloWorld.java'
            }
        }

        stage('Test') {
            steps {
                sh 'java -cp src HelloWorld'
            }
        }
    }
}
