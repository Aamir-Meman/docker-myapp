pipeline {
    agent none
    stages{
        stage('build'){
            agent{
                label 'myslavesmaven'
            }
            
            steps{
               echo "my fix branch"
               
            }
        }
    }
}
