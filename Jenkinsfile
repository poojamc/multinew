pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact"
               """
           }
       }
       stage('test Code') {
           steps {
               sh """
               echo "testing code"
               """
           }
       }
      stage('Delivery Code') {
          steps {
               sh """
               echo "Delivering Code"
               """
          }
      }
         stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}
