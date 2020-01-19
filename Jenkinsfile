pipeline {
    agent { docker { image 'ubuntu:latest' }  } 
    stages {
        stage('Build') {
            steps {
                sh '''
                    cd src
                    gcc src/prog.c
                    src/a.out	
                '''
            }
        }
    }
}
