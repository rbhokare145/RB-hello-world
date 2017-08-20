pipeline {
     agent any 
   
     stages { 
          
          stage ('Build') {
               
               when {
                    allOf {
                         
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

     
   
