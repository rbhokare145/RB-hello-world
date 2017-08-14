pipeline { 

     agent any  

      stages { 

    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '4aad76d5-0a61-4c5b-a236-8816f1a26686', url: 'https://github.com/rbhokare145/RB-hello-world']]])



         stage ('Build') {

             steps {

                     echo "Building" 

                   }
         }

       
         stage ('Test') {

            steps { 
 
                    echo "Testing" 

                  }

         }




         stage ('Deploy') {

             steps {

                       echo  "Deploying"


                   }

         }
 	
   }
}

