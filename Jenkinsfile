#!groovy
def currentBranch(branchName) {
    return env.BRANCH_NAME == branchName
    }
node {

  if (currentBranch('master')) {
   stage ('Checkout') {
   checkout scm
   }
  stage('Build') {  //Build steps go here
    mvn clean install
    } 
  }
  }
