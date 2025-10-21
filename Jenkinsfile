pipeline {
    agent any
    stages {
        stage('Preparar') {
            steps {
                echo '✅ Jenkins recibió el webhook correctamente'
            }
        }
        stage('Build falso') {
            steps {
                echo '🏗️ Simulando compilación del proyecto...'
            }
        }
        stage('Deploy falso') {
            steps {
                echo '🚀 Simulando despliegue exitoso!'
            }
        }
    }
}
