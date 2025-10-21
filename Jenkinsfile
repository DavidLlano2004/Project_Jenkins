pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compilando el proyecto...'
                bat './gradlew build'
            }
        }
        stage('Run') {
            steps {
                echo 'Iniciando el servidor Spring Boot...'
                bat './gradlew bootRun'
            }
        }
    }
}
