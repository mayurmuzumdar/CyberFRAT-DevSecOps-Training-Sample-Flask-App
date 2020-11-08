pipeline {
   agent any 

   stages {
     stage('Build Docker image') {
       steps {
              sh 'pwd'
              sh 'sudo docker build -t cyberfrat:$BUILD_NUMBER .'
                }
            }
        }
    }
