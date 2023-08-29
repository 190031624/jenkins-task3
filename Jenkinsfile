pipeline{
    agent any
    parameters{
       booleanParam(name: 'myBoolean', defaultValue: false, description: 'check this value') 
    }
    stages{
        stage('demo'){
            steps {
                echo "Hi ${!fparams.myBoolean}"
            }
        }
    }
}
