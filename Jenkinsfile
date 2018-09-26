pipeline{
    agent any
    stages{
        stage('Prereq'){
            steps {
                sh 'npm install'
            }
        }
        stage('Run unit Tests'){
            steps {
                sh 'npm test'
            }
        }
    }
}