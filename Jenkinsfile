pipeline {
    agent any
        stages {
            stage('package'){
                steps{

                    bat 'mvn clean'
                }
                post{
                    success{
                        echo 'now archiving'
                        

                    }
                }
            }
        }
}