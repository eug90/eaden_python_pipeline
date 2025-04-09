pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "pipe1 running"'
                sh '''
                    echo "or not????"
                    ls -lah
                '''
            }
        }
    }
}
