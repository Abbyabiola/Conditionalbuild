pipeline{
    agent any
    stages{
        stage('main branch deploy code'){
            when{
                branch 'main'
            }
            steps{
                echo "buiding artifact from main branch"
            }
        }
        stage('develop branch deploy code'){
            when{
                branch 'Develop'
            }
            steps{
                echo "buiding artifact branch from branch"
                echo "deploying code from develop branch"
            }
        }
    }
}