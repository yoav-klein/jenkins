pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                    cd src
                    gcc prog.c
                    ./a.out	
                '''
            }
        }
    }
}
