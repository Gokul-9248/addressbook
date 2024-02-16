pipeline{
  agent any
    stages {
      stage('checkout the code from github'){
        steps{
      git url:'https://github.com/Gokul-9248/addressbook.git'
        }
      }
      stage('building the source code'){
        steps{
      sh 'mvn compile'
        }
      }
      stage('testing the source code'){
        steps{
      sh 'mvn test'
        }
      }
      stage('package the source code'){
        steps{
      sh 'mvn clean package'
        }
      }
    }
}
