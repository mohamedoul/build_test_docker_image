pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
         
             steps {
                sh  '/root/.local/bin/anchore-cli image list'
            }

        }
    }
}
