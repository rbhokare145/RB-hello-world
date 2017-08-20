pipeline {
     agent any 
   
     stages { 
          
          stage ('Build') {
               
               when {
                    expression {
                         
                         "Foo" == "bar"
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

     
   
