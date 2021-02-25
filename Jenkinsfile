pipeline{
    agent any

    stages{
        stage("Checkout Code from SCM"){
            steps{
               git branch: 'master', url: 'https://github.com/abdallawi/jenkins-maven-plugin-01-simplepipline.git'
            }            
        }
         stage("Clean Up"){
            steps{
               echo "Hello from jenkinsfile"
            }            
        }
        stage("Compile it "){
            steps{
               
            }            
        }
        stage("Unit Tests "){
            steps{
               
            }            
        }
         stage("Package (i.e. Generale the deployable JAR)"){
            steps{
               
            }            
        }
    }