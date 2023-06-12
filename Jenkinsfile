pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
script {                sh 'echo "Hello, World!"'
}            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
script{                sh 'echo "Deploying application..."'
}            }
        }
    }
}
