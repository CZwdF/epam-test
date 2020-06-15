pipeline {
   agent any
   }

   stages {
      stage('Build') {
         steps {
            // Get some code from a GitHub repository
            git 'https://github.com/kriru/firstJava.git'
            sh 'javac HelloWorld.java
            sh 'java HelloWorld'
         }

         post {
 
            success {
               echo 'success'
            }
         }
      }
   }
}
