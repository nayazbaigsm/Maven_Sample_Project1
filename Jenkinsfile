pipeline{
    agent any
        stages{ 
            stage('Clone'){ 
                steps{
                 bat  'mvn install' 
                }
            }
            stage('Complete'){
                steps{
                   bat 'java -jar target/java-project2-1.0-SNAPSHOT.jar'  
                }
            }
        }
     }
