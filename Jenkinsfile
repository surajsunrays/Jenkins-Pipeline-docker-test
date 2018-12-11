pipeline {
    agent {
        docker 
        { 
            image 'hello-world' 
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'sudo docker run hello-world'
            }
        }
    }
}