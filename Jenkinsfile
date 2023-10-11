pipeline{
  agent any
  stages{
    stage("Deploy"){
      steps{
        echo"Test sucessfull"
        bat "mvn compile"
      }
    }
    stage("Build"){
      steps{
        echo"Build Sucessfull"
        bat "mvn clean"
      }
    }
    stage("Test"){
      steps{
        echo "Test sucessful"
        bat "mvn test"
      }
    }
  }
}
