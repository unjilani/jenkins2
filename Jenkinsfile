pipeline {
    agent any

    stages {
        stage('Execute shell script') {
            steps {
               script{
                chmod +x script.sh
                sh './script.sh'
               }
            }
        }
    }
}