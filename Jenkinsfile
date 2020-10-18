pipeline{
        agent any
        stages{
              stage('Test Phase Starts'){
                steps{
                echo 'start the test phase'
                }
              }
              
              stage('Test'){
                steps{
                sh 'mvn test'
                }
              }
              
              stage('Sonar phase starts'){
                steps{
                echo 'start the sonar phase'
                }
              }
                
                stage('Sonar'){
                steps{
                sh 'mvn sonar:sonar -Dsonar.host.url=http://localhost:9000 -Dsonar.analysis.mode=publish'
                }
              }
        }
     
}
