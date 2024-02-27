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
    stage("clean")
    {
      steps
      {
        sh "mvn clean"
      }
    }
    stage("validate")
    {
      steps
      {
        sh "mvn validate"
      }
    }
    stage("compile")
    {
      steps
      {
        sh "mvn compile"
      }
    }
    stage("test")
    {
      steps
      {
        sh "mvn test"
      }
    }
    stage("package")
    {
      steps
      {
        sh "mvn package"
      }
    }
    stage("install")
    {
      steps
      {
        sh "mvn install"
      }
    }
  }
}
