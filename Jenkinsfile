pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Verify branch ') {
            steps {
                echo "$GIT_BRANCH" }

        stage(' docker build ') {
            steps {
                sh 'docker images -a '
                sh 'docker build -t backend-app . '
                sh 'docker images -a '
                
                }
        }
    }
}
