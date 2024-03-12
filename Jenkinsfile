pipeline
{
  agent
  {
    label "slav"
  }
  stages
  {
    stage("GIT")
    {
      steps
      {
        git branch: 'main', url: 'https://github.com/udayakumar99/maven_project.git'
      }
    }
    stage("clean")
    {
      steps
      {
        sh "mvn clean"
      }
    }
    stage("install")
    {
      steps
      {
        sh "pwd"
      }
    }
  }
}
