pipeline{
    agent any
    stages{
        /*stage('checkout'){
            steps{
                git branch: 'main', 
                url: 'https://github.com/csah01/myps.git'
            }
        }*/
        stage('execute ps'){
            steps{
               powershell './helloWorld.ps1'
            }
        }
        
    }
}
