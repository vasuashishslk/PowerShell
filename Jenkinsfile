pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Deploy to production 1') {
            steps {
                echo 'Deploying to prod 1...'
      
            }
        }
        stage ('Depoly to production 2'){
            steps{
              echo 'Depolying to prod 2 ...'
          }
        }
        stage ('Deploy to production 3'){
            steps{
                 echo 'Depolying to prod 3 ..'
                 echo "TimeStamp: ${currentBuild.startTimeInMillis}"
                 
                 
               }
            }
            
    }
}
