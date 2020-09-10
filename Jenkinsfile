pipeline {
    agent any
    stages {
        stage ('git checkout'){
            steps{
                echo 'checkout from Rep1-Dev Branch'
            }
        }
        stage ('Build') {
            steps{
                echo 'first build on Rep1-Dev Branch'
            }
        }
        stage ('Deploy') {
            steps{
                echo 'first deploy on Rep1-Dev Branch'
            }
        }
    }
}
