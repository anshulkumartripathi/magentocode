pipeline {
  agent any
     
  stages {
    stage('Checkout SCM'){
      
    }
    stage('Execute shell commands'){
      steps {
        sh """
           cd /var/www/html/magento2/bin
           magnento setup:upgrade
           """
      }
    }
  }
