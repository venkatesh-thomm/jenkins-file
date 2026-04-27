pipeline{
    agent {
        node {
            label "AGENT-1"
        }
    }

    options{
        disableConcurrentBuilds()
    }
    
   
    stages{
        stage("SCM"){
            steps{
                echo "Checking out code from branch"
            }
        }

         stage("build"){
             steps{
                 echo "Building the code"
             }
        }
        
        stage("Test"){
            steps{
                echo "Testing the code"
            }
        }

         stage("Deploy"){
             steps{
                 echo "Deploying the code"
             }
         }
    }

}