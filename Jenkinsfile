pipeline{
    agent any

    stages{
        stage {
            steps{
                  sh 'sleep 5'
            }
        }
    
        stage {
            steps{
                  sh '''
                  #!/bin/bash
                  ls -lrt
                  sleep 5
                  '''
            }
        }
    }

}
