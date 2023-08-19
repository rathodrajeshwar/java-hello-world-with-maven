pipeline{
    agent any
    stages{
        stage{"git checkout"}{
            steps {
              git credentialsId: 'git_credentials', url: 'https://github.com/rathodrajeshwar/java-hello-world-with-maven.git'
            } 
        }
        stage{"Maven Build"}{
            steps{
               sh "mvn clean install"
         
            }
        }
    }
}
