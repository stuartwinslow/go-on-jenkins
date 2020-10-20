pipeline {
    agent { node { label 'master' } } 
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('Build') {
            steps {
                sh '/usr/local/go/bin/go build main.go'
            }
        }
    }
}
