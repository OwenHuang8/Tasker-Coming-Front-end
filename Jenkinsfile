pipeline{
    agent any
    
    stages {
        
        
        stage('Build'){
            steps{
                echo 'Building...'
//                 sh 'yarn && CI=false yarn build'
                
            }
        }
        
        stage('Testing'){
            steps{
                echo 'Testing...'
                
            }
        }
        
        stage('Deploying'){
            steps{
                echo 'Deploying...'
//                 withAWS(credentials: 'aws-credential', region:'ap-southeast-2'){
//                     sh 'aws s3 ls'
//                     sh 'aws s3 sync /var/lib/jenkins/workspace/byte-front-end/build s3://uat-front-end'
                }
            }
            
            
        }
    }
}
