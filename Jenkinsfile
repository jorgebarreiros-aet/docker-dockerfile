pipeline {
    agent {docker{
        image'python'
        }
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh '''#!/usr/bin/python3
name="Jenkins"
print('Hello {} from Python!'.format(name))'''
            }
        }
    }
}
