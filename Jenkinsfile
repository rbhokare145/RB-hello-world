pipeline {
     agent any 
   
     stages { 
          
          stage ('Build') {
               
               when {
                    allof {
                         
                         not { branch 'master' }
                    }    
                 
                  
               }
               
               steps {
                    sh '''
                     echo "Hello Welcome to Shell"
                     
                     '''
               }
               
          }
     }
     
}

     
   
