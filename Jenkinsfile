pipeline {
    agent any

    stages {
        stage('Execute shell script') {
            steps {
                script{
                    sh 'echo "Hello world !!"'
                    sh 'chmod 777 a.sh'
                    sh './a.sh'
                }
            }
        }
    }
}
