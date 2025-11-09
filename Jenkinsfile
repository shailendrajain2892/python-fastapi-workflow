pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git(
                    branch: 'main',
                    url: 'git@github.com:shailendrajain2892/python-fastapi-workflow.git',
                    credentialsId: 'cf83d05d-cb2a-4abf-8e17-5e823f89d900'
                )
            }
        }
        stage("build") {
            steps {
                echo "building the application"
            }
        }
        stage("test") {
            steps {
                echo "testing the application..."
            }
        }
        stage("deploy") {
            steps {
                echo "deploying the application..."
            }
        }
    }
}