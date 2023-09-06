pipeline {
   agent any
   stages {
       stage('Hello') {
           steps {
               echo "Hello world"
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
