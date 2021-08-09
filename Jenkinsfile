pipeline{
   agent any
      stages {
        stage('one') {
          steps{
             echo 'Hi, the CD/Ci pipeline working fine'
          }
        }
          stage('test') {
          steps{
              input('do you want to proceed?')
          }
        }
      }
}
