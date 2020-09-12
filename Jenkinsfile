pipeline {
    agent any
    stages {
        stage ('Build') {
            steps{
                echo 'first build on Rep1-Dev Branch'
				sh 'python Sample2.py'
            }
        }
        stage ('Deploy') {
            steps{
                echo 'first deploy on Rep1-Dev Branch'
            }
        }
    }
}
