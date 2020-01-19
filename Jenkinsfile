pipeline {
    agent any
        stages {
            stage('package'){
                steps{

                    bat 'mvn clean package'
                }
                post{
                    success{
                        echo 'now archiving'
                        

                    }
                }
            }
        }
}