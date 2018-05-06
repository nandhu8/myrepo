pipeline{
agent any
tools{
  maven 'mvncfg'
  }
  stages{
    stage('compile stage'){
      steps{
        sh 'mvn compile'
      }
    }
    stage('package style'){
      steps{
        sh('mvn package')
        }
        }
       }
      } 
