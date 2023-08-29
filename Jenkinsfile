pipeline{
    agent any
    stages{
        stage('demo'){
            steps {
                echo "Hi"
            }
            steps{
                script {
                    sh "kubectl apply -f deployment.yaml"
                }
            }
        }
    }
}
