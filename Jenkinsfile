pipeline{
  agent any
  stages{
    stage("Checkout to Github"){
      steps{
        git branch :"/main",
        url : "https://github.com/jayjadhav33/DevOps_Lab/"
      }
    }
    stage("Build Stage"){
      steps{
        bat "javac code.java"
      }
    }
    stage("Run Stage"){
      steps{
        bat "java code"
      }
    }
  }
}
