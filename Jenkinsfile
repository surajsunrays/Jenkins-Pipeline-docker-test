pipeline{
    agent{
        docker{
            image 'hello-world'
        }
        stages{
            stage('Running'){
                steps{
                    sh 'docker run hello-world'
                }
            }
            stage('Deploy'){
                steps{
                    echo "Operation Successfull..."
                }
            }
        }
    }
}