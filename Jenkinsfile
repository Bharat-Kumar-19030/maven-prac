pipeline{
    agent any
    stages{
        stage('compile'){
            steps{
                dir('demo'){
                    bat 'mvn compile'
                }
            }
        }
        stage('package'){
            steps{
                dir('demo'){
                    bat 'mvn package '
                    echo 'package completed'
                }

            }
        }
    }
}