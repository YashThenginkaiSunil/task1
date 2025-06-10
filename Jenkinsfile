pipeline{
    agent any

    stages{
        stage("details"){
            steps{
                sh """
                pwd
                whoami
                uptime
                echo $BUILD_ID
                echo $JOB_NAME
                hostname
                """
            }
        }
    }
}