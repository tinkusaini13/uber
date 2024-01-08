pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                  
                    git branch: 'main', url: 'https://github.com/tinkusaini13/uber.git'
                   
                }
            }
        }


        stage('Maven build'){
            
            steps{
                
                script{
                    
                    sh 'mvn clean package'
                }
            }
        }
    }
        
}
