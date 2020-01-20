pipeline {
    agent { label 'amitay'  } 
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
