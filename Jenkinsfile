currentBuild.displayName= "${env.BUILD_NUMBER}"
pipeline {
agent any 
 stages{
   stage("git clone"){
   steps{
     echo "hello and welcome"
    
    echo "commit is ${env.GIT_COMMIT[0..5]}"
       }
   }
 }
}

