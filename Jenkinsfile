pipeline {
agent any
  stage {
   stage ('Test') {
      steps {
        echo "Hello Test"
      }
    }
  stage ('Build') {
    steps {
      echo "Hello Build"
     }
    }
   }
  }
 def name='pipeline'
 pipeline {
   agent any
     stage {
       stage ('Deploy')
         steps {
           echo "Hello Deploy"
         }
       }
    }   
