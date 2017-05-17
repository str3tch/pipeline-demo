pipeline{
    agent{ docker 'node: 4.8.3-alpine'
    } 
    stages{
        stage('Example Build'){
            steps{
                sh 'node --version'
            }
        }
        stage('Hello world'){
            steps{
                sh 'echo hello'
            }
        }
    }
}
