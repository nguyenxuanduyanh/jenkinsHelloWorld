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
    stage("Email Stage"){
      steps{
       emailext body: 'Hahaha, Fail', subject: 'TestTest', to: 'anhnxd.b8014@st.usth.edu.vn'
      }
    }
  }
}
