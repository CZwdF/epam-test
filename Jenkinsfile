  
pipeline {
    agent any 
    stages {

   stage('build and deploy') {
            when {
                branch 'master'
            }
            steps {
                echo 'build and deploy stuff'
               
            }
        }
        stage('Only build') {
            when {
                branch 'zzz'
            }
            steps {
                echo 'only build a source code'
                
            }
        }
    }
}
