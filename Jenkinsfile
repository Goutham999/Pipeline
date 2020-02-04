pipeline {
  agent any
    stages{
      stage('One'){
        steps{
          echo 'THis is stage 1'
        }
      }
      stage('Two'){
        steps{
          echo 'This is stage 2'
        }
      }
      parallel{
      stage('Three'){
        steps{
          echo 'THis is stage 3'
        }
      }
      stage('Four'){
        steps{
          echo 'This is stage 4'
        }
      }
     }
  }
}
