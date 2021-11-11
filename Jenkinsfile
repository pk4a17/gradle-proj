pipeline{
    agent any
    stages{
        stage('Message'){
            steps{
                echo 'Hello, This is Jenkins pipeline.'
            }
        }
        
        stage('Permission'){
            steps{
                input('Do you want to proceed?')
            }
        }
        
        stage('Mail'){
            steps{
                mail bcc: '', body: 'Jenkins sample-pipeline build is successfull!', cc: '', from: '', replyTo: '', subject: 'Build successfull', to: 'purushottam.k@fnp.com'
            }
        }
    }
}
