pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo 'Building the application...'
                // Example: compile or build step
                // sh 'npm install' or 'mvn package' etc.
            }
        }

        stage("Test") {
            steps {
                echo 'Running tests...'
                // Example test command
                // sh 'npm test' or 'pytest tests/' etc.
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Example deploy command
                // sh './deploy.sh'
            }
        }
    }
}
