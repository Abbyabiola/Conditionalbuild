pipeline{
    agent any
    stages{
        stage('Main branch deploy code'){
            when{
                branch 'main'
            }
            steps{
                echo 'main branch deploy code'
                echo ' Buiding artifact from main branch'

                echo "buiding artifact from main branch"
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
