pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Running build in ${env.BRANCH_NAME} ....'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests in ${env.BRANCH_NAME} ....'
            }
        }
    }
}