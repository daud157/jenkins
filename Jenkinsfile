

pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('test'){
            steps{
              sh 'echo "Hello World test is running and i am sitting in library"'
              sh 'echo "i  am testing my application"'           
            }
        }
        stage('deploy'){
            steps{
                sh 'echo "deploying phase '
            }
        }
    }
}

