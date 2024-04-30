pipeline{
  agent any
    stages{
        stage('build'){
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
                sh 'echo "deploying phase'
            }
        }
        }
    }





}