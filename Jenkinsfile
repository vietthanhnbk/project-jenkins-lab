pipeline {
    agent any
    stages {
        stage('Build Main') {
            when {
                 changeset "*.js"
            }
            steps {
                echo 'Hello World changing JS'
            }
        }
    }
}
