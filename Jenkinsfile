pipeline {
    agent { label 'linux' }
    
    options {
        buildDiscarder(logRotator(artifactDaysToKeepStr: '7', artifactNumToKeepStr: '5', daysToKeepStr: '7', numToKeepStr: '5'))
        disableConcurrentBuilds()
    }
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello, World!'
            }
        }
    }
}
