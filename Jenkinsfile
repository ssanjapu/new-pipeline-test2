pipeline
{
 agent any
 stages{
  stage('Build Application'){
  steps{
   bat 'C:\Softwares\apache-maven-3.6.3\bin\mvn clean install'
  }
  }  
  stage('Deploy application to Mulesoft CloudHub '){
  steps{
   bat 'C:\Softwares\apache-maven-3.6.3\bin\mvn package deploy -DmuleDeploy'
  }
  }
 }
}