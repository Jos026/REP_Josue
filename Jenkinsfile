pipeline {
    agent{
        label 'windows'
    }

    stages {
        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }
    }
    stages {
        stage('Unit Test') {
            steps {
                echo 'Ejecutando Unit Test'
            }
        }
    }
    stages {
        stage('Build Application') {
            steps {
                bat 'ng build'
            }
        }
    }
}