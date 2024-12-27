pipeline {
    agent any

    stages {
        stage('Execute shell script') {
            steps {
                script{
                    sh 'chmod 777 script.sh'
                    sh './script.sh'
                }
            }
        }
    }
}
