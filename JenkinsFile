pipeline{
  agent any
  stages{
    stage("make directory")}
      steps{
        sh "mkdir ~/first-jenkins-test"
      }
    }
    stage("make files"){
      steps{
        sh "touch ~/first-jenkins-test/myfile1"
      }
    }
  }
}
