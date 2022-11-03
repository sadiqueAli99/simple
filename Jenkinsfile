pipeline{
    agent any
    stages{
        stage('Git Clone'){
            steps{
            git branch: 'master', url: 'https://github.com/sadiqueAli99/simple.git'
               }
        }
        stage('Maven Test'){
        steps{
          print('tested')
             }
            
        }
        
        stage('Maven Deploy'){
        steps{
           print('deployed')
             }
        }
    }
}
