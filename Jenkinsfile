pipeline{
    agent any
    stages{
        stage("update version"){
            steps{
                sh 'update version'
            }
        }
        stage("Build Project"){
            steps{
             sh 'echo this is build project'   
            }
        }
        stage("Create Docker image"){
            steps{
              sh "create docker image"
            }
        }
        stage("put into jfrog artifactory"){
            steps{
                sh 'echo push artifactory'
            }
        }
        stage("deploy into virtual machine"){
            steps{
                sh 'deploy into ec2 machine'
            }
        }
    }
}
