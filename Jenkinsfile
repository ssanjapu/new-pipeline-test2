pipeline
{
 agent any
 stages{
  
  stage('Build Application'){
  steps{
  mvn clean install
  }
  }  
  stage('Deploy application to Mulesoft CloudHub '){
  steps{
  mvn package deploy -DmuleDeploy
  }
  }
 }
}