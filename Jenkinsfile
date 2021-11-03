pipeline {
    agent {docker 'python'}
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'python hello.py'
            }
        }
    }
}
