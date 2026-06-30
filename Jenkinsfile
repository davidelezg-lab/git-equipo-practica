pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build OK'
            }
        }

        stage('Test') {
            steps {
                error 'Test fallido'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy OK'
            }
        }
    }
}
