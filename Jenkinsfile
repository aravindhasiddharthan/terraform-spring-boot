pipeline{
   agent any
      stages {
    
          stage('entry') {
          steps{
              input('do you want to proceed?')
          }
        }
          stage('git clone') {
          steps{
              git 'https://github.com/aravindhasiddharthan/terraform-spring-boot.git'
          }
        }
      }
}
