pipeline {
    agent { docker { image 'ubuntu:latest' } } 
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    ls -lah
                '''
            }
        }
    }
}
