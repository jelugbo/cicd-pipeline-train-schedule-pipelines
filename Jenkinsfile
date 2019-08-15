pipeline{
  agent any
  stages{
   stage ('build'){
    steps{
      echo 'Running Build Automation'
      sh './gradlew build -- no-daemon'
      archiveArtifacts artifacts: dish/trainSchedule.zip
    }
  
    }
  }
