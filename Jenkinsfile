pipeline{
        agent any
        stages{
              stage('Build'){
                steps{
                echo 'Build stage'
                }
              }
              
              stage('Test'){
                steps{
                sh 'mvn test'
                }
              }
              
              stage('Deploy'){
                steps{
                echo 'Deploy stage'
                }
              }
        }
     
}
