pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                    echo 'Hello World'
                '''
            }
        }
        stage('Test'){
            steps{
                sh '''
                    echo "Test is in progress"
                '''
            }
        }
        stage(''){
            steps {
                sh 'echo "Releasing"'
            }
        }
    }
}
