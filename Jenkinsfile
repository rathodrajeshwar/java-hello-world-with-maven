pipeline{
    agent any
    stages{
       stage{"Git Checkout"}{
          steps{
              https://github.com/rathodrajeshwar/java-hello-world-with-maven.git
          
          }
       }
       stage{"Maven Build"}{
          steps{
              sh "mvn clean install"
         
          }
       }
    }
}
