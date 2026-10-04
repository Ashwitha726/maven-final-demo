pipeline {
    agent {
        label 'linux-agent'
    }

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code is already available.'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }
}