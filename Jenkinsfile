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
         tage('Deploy') {
            steps {
                script{
                deploy()
                }
            }
        }
    }
}
