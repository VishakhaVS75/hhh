pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac add.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java add'
            }
        }
    }
}
