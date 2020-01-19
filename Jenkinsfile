pipeline {
    agent any
        stages {
            stage('package'){
                steps{

                    sh 'mvn clean package'
                }
                post{
                    success{
                        echo 'now archiving'
                        archiveArtifacts artifacts: '**/target/*.war'

                    }
                }
            }
        }
}