pipeline {
 agent any
  stages{
    stage("Cleaning Stage"){
      steps{
      echo "Inside Cleaning Stage"
      }
  }
  
    stage("Finish Stage"){
      steps{
            echo "Inside Finish Stage"
      }
    }
    stage("Test Stage"){
      steps{
        input("Do you wanna test this build")
        echo "Inside Test Stage"
      }
    }
  }
}
