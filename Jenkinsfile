pipeline {
    agent any

    stages {
        stage('Execute shell script') {
            steps {
                script{
                    sh 'echo "Hello world from Jenkins server!"'
                    sh 'chmod 777 a.sh'
                    sh './a.sh'
                    sh 'chmod 777 script.sh'
                    sh './script.sh'
                }
            }
        }
    }
}
