pipeline {
     
     agent any 
     
     stages {
          stage('Browser test') { 
          parallel {
               stage ('Chrome') { 
                    steps{      
                                sh ''' 
                                echo "Testing on Chrome"
                                '''
                    }
               }
             
               stage('Firefox') {
                    steps {
                           sh '''
                           echo "Testing on Firefox"
                          }
               }
               
          }
       }
       
    }
    
    }
    
