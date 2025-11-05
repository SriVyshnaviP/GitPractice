pipeline{
    agent any
    triggers {
        githubPush()
    }
    stages{
        stage('shell'){
            steps{
                sh 'Webhook triggered for pipeline'
            }
        }
    }
}
