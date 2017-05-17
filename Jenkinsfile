pipeline{
    agent{ docker 'node:4.8.3-alpine'
    } 
    stages{
        stage('show version'){
            steps{
                sh 'node --version'
            }
        }
        stage('Hello world'){
            steps{
                sh 'echo hello'
            }
        }
        stage('Hello Perth!'){
            steps{
                sh 'echo Hello Perth'
            }
        }
    }
}
