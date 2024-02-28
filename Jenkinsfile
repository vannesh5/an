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
    stage("install")
    {
      steps
      {
        sh "mvn install"
      }
    }
    stage("git 1")
    {
      steps
      {
        git 'https://github.com/udayakumar99/sample26.git'
      }
    }
    stage("running")
    {
      steps
      {
        sh "java Demo.java"
      }
    }
  }
}
