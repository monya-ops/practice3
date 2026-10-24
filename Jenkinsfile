pipeline
{
  agent any {
      triggers{
        pollSCM('H/5 * * * * ')
      }
    stages{
      stage('Build'){
        steps{
          git 'https://github.com/monya-ops/practice3'
          echo 'Build Successful"
        }
      }
    }
  }
