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
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}
