Pipeline {
agent any
  stages {
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
 Pipeline {
   agent any
     stages {
       stage ('Deploy')
         steps {
           echo "Hello Deploy"
         }
       }
    }   
