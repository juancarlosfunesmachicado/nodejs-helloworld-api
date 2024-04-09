pipeline {
    agent any
    //
    tools {nodejs '21.7.1'}
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
