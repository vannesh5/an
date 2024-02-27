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
    stage("clean")
    {
      steps
      {
        bat "mvn clean"
      }
    }
    stage("validate")
    {
      steps
      {
        bat "mvn validate"
      }
    }
    stage("compile")
    {
      steps
      {
        bat "mvn compile"
      }
    }
    stage("test")
    {
      steps
      {
        bat "mvn test"
      }
    }
    stage("package")
    {
      steps
      {
        bat "mvn package"
      }
    }
    stage("install")
    {
      steps
      {
        bat "mvn install"
      }
    }
  }
}
