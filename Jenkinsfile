pipeline {
    agent any
    stages{
        stage('stage 1'){
            steps{
                println 'first test echo'
            }
        }
        stage('stage 2'){
            steps{
                input('Wanna proceed?')
            }
        }
        stage('stage 3'){
            steps{
                println('this is stage 3')
            }
        }
    }
}
