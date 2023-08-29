pipeline{
    agent any
    stages{
        stage('demo'){
            steps{
                script {
                    sh "kubectl apply -f deployment.yaml"
                }
            }
        }
    }
}
