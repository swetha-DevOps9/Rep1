pipeline {
    agent any
    stages {
        stage ('git checkout'){
            steps{
                echo 'checkout from Rep1-QA Branch'
            }
        }
        stage ('Build') {
            steps{
                echo 'first build on Rep1-QA Branch'
            }
        }
        stage ('Deploy') {
            steps{
                echo 'first deploy on Rep1-QA Branch'
            }
        }
    }
}
