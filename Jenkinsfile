pipeline{
    agent any
   options { retry(3) }
   triggers{ cron('H(0-29)/10 * * * *') } // every 10 minutes
    
    
    stages{

        stage('buildingStage'){


            steps{

                sh "building now"
            }
        }


        stage('testingStage'){


            steps{

               sh "testing now"
            }
        }



        stage('deployingStage'){


            steps{

                sh "deploying now"
            }
        }



    }


}
