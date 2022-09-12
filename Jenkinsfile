pipeline {
    agent any
    stages {
       stage('Build'){
           steps{
           sh 'echo "Building the code.."'
           sh 'tree'
           sh 'date'
          }
       }
       stage('Test'){
           steps{
             echo "Testing the code.."
           }
       }
       stage('QA'){
            steps{
              echo "QA Analysis.."
           }
       }
       stage('Deploy'){
            steps{
              echo "Deploying the code.."
           }
       }
       stage('Monitor'){
            steps{
              echo "Monitoring the code.."
            }
       }
     }
}
