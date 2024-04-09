pipeline {
    agent any
    // Ejemplo
    stages {
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }   
}
