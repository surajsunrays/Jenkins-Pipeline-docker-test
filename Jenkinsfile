pipeline {
    agent {
        docker 
        { 
            image 'maven' 
        }
    }
    stages {
        stage('Test Java') {
            steps {
                sh 'java -version'
            }
        }
        stage('Test Maven'){
            steps{
                sh 'mvn --version'
            }
        }
        }
    }
