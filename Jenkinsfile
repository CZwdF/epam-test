  
pipeline {
    agent any 
    stages {

   stage('Deliver for development') {
            when {
                branch 'master'
            }
            steps {
                sh 'cat README.md'
               
            }
        }
        stage('Deploy for production') {
            when {
                branch 'zzz'
            }
            steps {
                sh 'cat README.md'
                
            }
        }
    }
}
