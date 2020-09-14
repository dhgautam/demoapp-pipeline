pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo "Running build in branch ${env.BRANCH_NAME} ...."
                echo "Adding new piece of code"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests in branch ${env.BRANCH_NAME} ...."
            }
        }
    }
}
