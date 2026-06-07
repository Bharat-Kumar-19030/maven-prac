pipeline{
    agent any
    stages{
        stage('compile'){
            steps{
                bat 'mvn compile'
            }
        }
        stage('package'){
            steps{
                bat 'mvn package ',
                echo 'package completed'
            }
        }
    }
}