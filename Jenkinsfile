
pipeline{
    agent any
  tools{
    maven 'MAVEN'
  }
    stages{
        stage('Clean'){
            steps{
                sh 'mvn clean'
            }
        }
    stage('Package'){
            steps{
                sh 'mvn package'
            }
        }
   
    }
    
}

