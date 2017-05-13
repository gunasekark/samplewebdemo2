#!groovy

node {


   stage ('Checkout') {
   checkout scm
   }
  stage('Build') {  //Build steps go here
    mvn clean install
    } 
 
  }
