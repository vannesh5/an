pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/udayakumar99/maven_project.git"
      }
    }
    stage("Run")
    {
      steps
      {
       sh "mvn clean"
       sh "java demo.java"
      }
    }
  }
}
