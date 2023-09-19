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
        stage('Release'){
            steps {
                sh 'echo "Releasing"'
            }
        }
    }
}
