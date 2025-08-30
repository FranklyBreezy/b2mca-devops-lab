pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running build step...'
                sh './app.sh'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh './test.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy step - simulated'
                echo 'Deployment complete.'
            }
        }
    }
}
