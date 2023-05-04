@Library("sharedlib") _
pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                script{
                build("Ashwath")
                }
            }
        }
                stage('Build') {
            steps {
                script{
                build()
                }
            }
        }
                stage('Deploy') {
            steps {
                script{
                deploy()
                }
            }
        }
    }
}
