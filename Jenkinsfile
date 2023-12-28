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
                sh 'sleep 15'
                echo "Checking...................!"
            }
        }
        stage("Release"){
            steps{
                sh 'sleep 20'
                echo "Checking...................!"
            }
        }
      
                  
    }
}
