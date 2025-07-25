pipeline {
    agent any
    stages{
        stage("making a directory"){
            steps{
                sh "mkdir ~/jenkins-test || true"
            }
        }
        stage("making a file"){
            steps{
                sh "touch ~/jenkins-test/file1.txt"
            }
        }
    }
}
