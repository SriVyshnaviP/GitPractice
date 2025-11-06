pipeline {
    agent any

    triggers {
        // Check Git repo for new commits every 2 minutes
        pollSCM('H/2 * * * *')
    }
     stages{
     stage('echo'){
         steps{
         echo 'success'
     }
}
     }
}
