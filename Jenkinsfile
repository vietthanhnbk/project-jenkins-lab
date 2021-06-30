pipeline {
    agent any
    stages {
        stage('Build Main') {
            when {
                 changeRequest()
            }
            steps {
                echo 'Building main'
            }
        }
    }
}
