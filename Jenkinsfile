#!/usr/bin/env groovy
pipeline{
  
       agent any
 
    stages{
        stage('Installing Tools'){
        
            steps{
                      echo "Something"
                   }
              }
              
              stage('Checkout Scm '){
        
            steps{
                      checkout scm
                   }
              }


        stage('Build Image'){
            steps{
             
           
                sh 'docker -v'
                sh'docker images' 
                sh 'docker build --tag keycodeproject .'
     
              
            }
        }
            

        stage('Run Application'){
            steps{
              echo "Something"
              sh 'docker run -t keycode'
        
            }
        }

        stage('Testing the application'){
            steps{ 
                  echo "Something"
            }
        }

        stage('Deploy'){
            steps{
                echo "Something"
                
            }
        }
    }
}

© 2019 GitHub, Inc.
