pipeline {
   agent any 

   stages {
     stage('Build Docker image') {
       steps {
         sh 'docker build -t cyberfrat:$BUILD_NUMBER .'
                }
            }
        }
    }