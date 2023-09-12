pipeline{
    agent any
    stages {
        stage('one') {
            steps{
                echo 'Hello, Pipeline is triggered.'
            }
        }
        stage('two'){
            steps{
                echo 'listing the current directory contents'
                sh 'ls -alh'
            }
        }
    }
}