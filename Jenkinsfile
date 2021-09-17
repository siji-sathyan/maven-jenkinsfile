
pipeline{
    agent any
  tools{
    maven 'MAVEN'
  }
    environment{
        PATH="%SystemRoot%\system32;%SystemRoot%;D:\POS\apache-maven-3.3.3-bin\apache-maven-3.3.3\bin;"
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

