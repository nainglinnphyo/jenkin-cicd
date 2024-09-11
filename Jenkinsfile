pipeline {
     agent any
     stages{
          stage('checkout'){
               steps{
                    checkout scm
               }
          }
          stage('Install Dev'){
               steps{
                    sh `sudo npm install`
               }
          }
           stage('Run'){
               steps{
                     sh `sudo node index.js`
               }
          }
     }
}