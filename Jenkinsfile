@Library("sharedlib") _
pipeline {
    agent any

    stages {
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
