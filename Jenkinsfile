
// Edited on Feature branch
node('master') 
{
  stage('ContinuousDownload') 
  {
    //git 'https://github.com/selenium-saikrishna/maven.git'
    git 'https://github.com/m-chiranjeevi1/maven.git'
  } 
/*  stage('ContinuousBuild') 
  {
    sh 'mvn package'
  } 
  stage('ContinuousDeployment') 
  {
    sh 'scp /home/vagrant/.jenkins/workspace/ScriptedPipeline/webapp/target/webapp.war vagrant@10.0.0.51:/var/lib/tomcat7/webapps/qaenv.war'
  } */
  stage('ContinuousTesting') 
  {
    // git 'https://github.com/selenium-saikrishna/TestingOnLinux.git'
    sh 'echo "hello jenkins"'  
  }
/*  stage('ContinuousDelivery') 
  {
      input message: 'Waiting for approval !', submitter: 'Venu'
    sh 'scp /home/vagrant/.jenkins/workspace/ScriptedPipeline/webapp/target/webapp.war vagrant@10.0.0.52:/var/lib/tomcat7/webapps/prodenv.war'
  } */
   
}
