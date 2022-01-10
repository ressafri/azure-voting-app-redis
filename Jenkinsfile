pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_BRANCH"
         }
      }
      stage('Hello world') {
         steps {
           sh(script: 'echo Hello World')
        }
     }
   }
}
