pipeline{
        agent any
        stages{
              stage('Start'){
                steps{
                echo 'start the pipeline'
                }
              }
              
              stage('Clean'){
                steps{
                sh 'mvn clean'
                }
              }
              
              stage('Install'){
                steps{
                sh 'mvn install'
                }
              }
        }
     
}
