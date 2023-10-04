pipeline{
    agent any
    stages{
        stage('main branch deploy code'){
            when{
                branch 'main'
            }
            steps{
                echo 'main branch deploy code'
                echo ' Buiding artifact from main branch'
            }
        }
        stage('develop branch deploy code'){
            when{
                branch 'develop'
            }
            steps{
                echo 'Develop branch deploy code'
                echo ' Buiding artifact from develop branch'
            }
        }
    }
}
