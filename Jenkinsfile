pipeline {
    agent none
    stages {
        stage('Build') {
             steps {
                echo "Build Step"
                  }
               agent {
                   docker {
                     image 'python:2-alpine' 
                          }
                      }
          }
        stage('Test') {
            
             steps {
                echo "Build Test"
            }
        }
        stage('Deliver') {
           
             steps {
                echo "Build Deliver"
            }
        }
    }
}
