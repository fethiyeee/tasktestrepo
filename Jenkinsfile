pipeline {
   agent any
   stages {
       stage('Hello') {
           steps {
               echo "Hello beautiful world"
                   }
           }
       }
   post{
       always{
           mail to: "fethiye0623@gmail.com",
           subject: "Test Email",
           body: "Test"
       }
   }
}
