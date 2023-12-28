pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Hi this going to build the"
            }
        }
        stage("Test"){
            steps{
                sh 'sleep 10'
                echo "Testing.................!"
            }
        }
          stage("Q&A"){
            steps{
                sh 'sleep 30'
                echo "Checking...................!"
            }
        }
      
                  
    }
}
