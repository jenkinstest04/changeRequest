pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                changeRequest()
            }
            steps{
                echo "Building successfully"
            }
        }
      
    }
}
