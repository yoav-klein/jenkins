pipeline {
    agent { docker { image 'ubuntu:latest' }  } 
    stages {
        stage('Build') {
            steps {
                sh '''
                    pwd
                    ls -lah
                    gcc src/prog.c
                    src/a.out	
                '''
            }
        }
    }
}
