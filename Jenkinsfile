pipeline{
    agent any
    stages{
        stage('One'){
            steps{
                echo 'Hello, This is Jenkins pipeline.'
            }
        }
        
        stage('Two'){
            steps{
                input('Do you want to proceed?')
            }
        }
        
        stage('Three'){
            steps{
                echo 'Moved to final stage!'
            }
        }
    }
}
