pipeline {
    agent any
    stages {
        stage('Build Main') {
            when {
                 changeset glob: ".js"
            }
            steps {
                echo 'Hello World changing JS'
            }
        }
    }
}
