pipeline {
    agent any
 	   stages {
       			 stage('build') {
    					        steps {
           						     echo 'build successfully'
            }
     					   }
stage('test') {
    					        steps {
           						     echo 'Tested successfully '
            }
     					   }

stage('deploy') {
    					        steps {
           						     echo 'deploy successfully '
            }
     					   }

   		 }
   		 post {
    					        always {
           						   emailext body: 'aaaa', subject: 'aaa', to: 'avinashbundela@gmail.com'
            }
     					   }
}
