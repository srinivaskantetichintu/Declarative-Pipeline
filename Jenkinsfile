//Declarative//
pipeline {
        agent any
        options {     // to skip default scm checkout in Declarative mode//
        skipDefaultCheckout() 
        }
        stages {
              stage ('Build') {
                   steps {
                        echo 'Building..'
                   }   
              }
              stage ('Test') {
                   steps {
                        echo 'Testing..'
                   }         
              }
              stage ('Deploy') {
                   steps {
                        echo 'Deploying..'
                   }
              }
        }
}
