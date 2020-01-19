pipeline {
    agent { docker { image 'yoavklein3/myimage2' } } 
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
