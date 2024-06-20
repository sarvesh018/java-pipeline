pipeline{
    agent any
    environment{
        VERSION_NAME="1.11"
    }
    stages{

        stage("compile"){

            steps{
                sh 'javac Test.java'
                sh 'echo "${VERSION_NAME}"'
            }

        }

        stage("run"){

            steps{
                sh 'java Test'
            }

        }
    }
}