pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git branch: 'main', url: 'https://github.com/udayakumar99/maven_project.git'
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
