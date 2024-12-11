pipeline{
    agent any
        stages{ 
            stage('Clone'){ 
                steps{
                 sh 'mvn install' 
                }
            }
            stage('Complete'){
                steps{
               sh 'java -jar target/java-project2-1.0-SNAPSHOT.jar' 
                }
            }
        }
     }
