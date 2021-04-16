pipeline {
    agent none
    stages{
        stage('build'){
            agent{
                label 'myslavesmaven'
            }
            
            steps{
               echo "git downloading.."
               git 'https://github.com/Aamir-Meman/docker-myapp.git'
               stash includes: '*', name: 'myapp' 
            }
        }
    }
}
