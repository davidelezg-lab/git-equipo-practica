pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Descargando código...'
            }
        }

        stage('Build') {
            steps {
                echo 'Compilando...'
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando tests...'
            }
        }

        stage('Analysis') {
            steps {
                echo 'Analizando calidad...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Desplegando...'
            }
        }
    }
}

