pipeline{
    agent any

    stages{
        stage("Install npm dependencies"){
            steps{
                sh "npm install"
            }
        }
        stage("Run tests"){
            steps{
                sh "npm test"
            }
        }
    }
}