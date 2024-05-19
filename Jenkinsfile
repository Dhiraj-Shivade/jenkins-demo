pipeline {
    agent any

    stages {
        stage('Executable permission for shell script') {
            steps {
               script{
                sh 'chmod 400 script.sh'
               }
            }
        stage('Execute shell script') {
            steps {
               script{
                sh './script.sh'
               }
            }
        }
    }
}