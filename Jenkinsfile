pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/SreekanthJaladanki/sample_maven_project.git"
      }
    }
    stage("Run")
    {
      steps
      {
       sh "mvn validate"
      }
    }
  }
}
