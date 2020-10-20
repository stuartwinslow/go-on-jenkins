pipeline {
    agent 'master'
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
