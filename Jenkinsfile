pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies and file uploaded appa') { 
        steps { 
          nodejs('NODEJS') {
           sh 'npm install' 
          }
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
