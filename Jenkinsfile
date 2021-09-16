
pipeline{
    agent any
  tools{
    maven 'MAVEN'
  }
    environment{
        PATH="C:\Program Files\Git\usr\bin"
    }
    stages{
        stage('Clean'){
            steps{
                bat 'mvn clean'
            }
        }
    stage('Package'){
            steps{
                bat 'mvn package'
            }
        }
   
    }
    
}

