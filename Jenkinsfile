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
        
        }
    }
}
