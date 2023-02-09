pipeline{
    agent any
    Tools{
        maven 'maven'
    }
        stages{
            stage('clean the workspace'){
                steps{
                echo 'clean the workspace'
                sh 'mvn clean'
            }
           }
           stage('building the image'){
            steps{
                echo 'clean the workspace'
                sh 'mvn install'
            }
           }
        }
    }
