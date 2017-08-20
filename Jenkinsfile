pipeline {
     agent any 
   
     stages { 
          
          stage ('Build') {
               
               when {
                    expression {
                         
                         "Foo" == "bar"
                    }
               }
               
               step {
                    sh '''
                     echo "Hello Welcome to Shell"
                    '''
               }
               
          }
     }
     
     
   
