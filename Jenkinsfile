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
        bat "javac Demo.java"
        bat "java Demo.java"
      }
    }
    stage("clean")
    {
      steps
      {
        "mvn clean"
      }
    }
    stage("validate")
    {
      steps
      {
        "mvn validate"
      }
    }
    stage("compile")
    {
      steps
      {
        "mvn test"
      }
    }
    stage("package")
    {
      steps
      {
        "mvn package"
      }
    }
    stage("install")
    {
      steps
      {
        "mvn install"
      }
    }
  }
}
