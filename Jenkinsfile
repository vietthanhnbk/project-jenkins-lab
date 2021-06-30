pipeline {
    agent any
    stages {
        stage('Build issue1') {
            when {
                branch 'issue1'
            }
            steps {
                echo 'Building issue1'
            }
        }
    }
}
