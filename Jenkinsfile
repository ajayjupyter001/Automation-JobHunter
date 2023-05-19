pipeline{
    agent any
    stages{
        stage("update version"){
            steps{
                sh "echo update version"
            }
        }
        stage("Build Project"){
            steps{
             sh "echo this is build project"  
            }
        }
        stage("Create Docker image"){
            steps{
              sh "echo create docker image"
            }
        }
        stage("put into jfrog artifactory"){
            steps{
                sh 'echo push artifactory'
            }
        }
        stage("deploy into virtual machine"){
            steps{
                sh 'echo deploy into ec2 machine'
            }
        }
    }
}
