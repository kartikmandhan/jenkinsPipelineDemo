pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building using Makefile...'
                sh 'make'
            }
        }
    }
}
