pipeline {
   agent any
    stages {
        stage('Checkout& Build ') {
            steps {
                echo " Checking Out code from Git Repo"
               echo " Compiling and Building code...."
            }
        }
        stage('Deploy code FE1') {
            steps {
                echo " Code is deployed on FE1 environment"
            }
        stage('Deploy on SIT') {
            steps {
              echo " Code is deployed on SIT environment"
            }
              
       stage('Deploy on UAT') {
            steps {
               echo " Code is deployed on UAT environment"
            }
        stage('Deploy on Prod ') {
            steps {
                echo " Code is deployed on PROD environment"
            }
        }
    }
}
