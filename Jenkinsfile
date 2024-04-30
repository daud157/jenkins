pipeline{
  agent any
    stages{
        stage('Build'){
            steps{
                sh 'npm install'
            }
                    }
            
        stage('test'){
            steps{
                sh 'echo "Test is running"'

            
            }
        steps('deploy'){
            steps{
                sh 'echo "deploying phase"'
            }
        }
        }
    }





}