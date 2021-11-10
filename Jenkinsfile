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
        
        stage('Mail'){
            steps{
                mail bcc: '', body: 'Jenkins sample-pipeline build is successfull!', cc: '', from: '', replyTo: '', subject: 'Build successfull', to: 'nikkikumar87615@gmail.com'
            }
        }
    }
}
