pipeline {
    agent { docker { image 'ubuntu:latest' }  } 
    stages {
        stage('Build') {
            steps {
                sh '''
                    ./a.out
                '''
            }
        }
    }
}
