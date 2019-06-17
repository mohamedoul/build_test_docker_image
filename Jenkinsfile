pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {

             steps {
                sh  '/root/.local/bin/anchore-cli image list'
            }

        }
    }
}
