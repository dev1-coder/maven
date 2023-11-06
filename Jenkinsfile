pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Compiling Java code...'
                    sh 'javac HelloWorld.java'
                }
            }
        }

        stage('Run') {
            steps {
                script {
                    echo 'Running Java program...'
                    sh 'java HelloWorld'
                }
            }
        }
    }
}
