pipeline {
    agent any 
    stages {
       stage ('Checkout') {
         when {
             expression {
                 BRANCH_NAME == 'master'
             }
         }      
         steps {
            echo "Sit"
         }
       }
    }
}    
    
