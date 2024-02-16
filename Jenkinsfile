pipeline{
  agent = 
    stages {
      stage= ('checkout the code from github'){
        steps{
      git url:''
        }
      }
      stage= ('building the source code'){
        steps{
      sh 'mvn compile'
        }
      }
      stage= ('testing the source code'){
        steps{
      sh 'mvn test'
        }
      }
      stage= ('package the source code'){
        steps{
      sh 'mvn clean package'
        }
      }
      
