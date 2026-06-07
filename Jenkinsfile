pipeline{
    agent any
    stages{
        stage('compile'){
            bat 'mvn compile'
        }
        stage('package'){
            bat 'mvn package'
        }
    }
}