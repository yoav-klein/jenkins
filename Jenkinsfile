pipeline {
    agent { docker { image 'ubuntu:latest' }  } 
    stages {
        stage('Build') {
            steps {
                sh '''
                    pwd
                    gcc src/prog.c
                    src/a.out	
                '''
            }
        }
    }
}
