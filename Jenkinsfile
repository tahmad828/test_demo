pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // build commands
            }
        }

        stage('Test') {
            steps {
                echo 'Testing..'
                // test commands
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying....'
                // deployment commands
            }
        }
    }

    post {
        always {
            echo 'Build condition running'
        }

        failure {
            echo 'Post Action if Build Failed'
        }
    }
}

