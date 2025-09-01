def gv
pipeline{
    agent any

    stages{
        stage("Initialization Stage"){
            steps{
                script{
                    gv= load "script.groovy"
                }
            }
        }
        stage('Run Build App'){
            steps{
                script {
                    gv.buildApp()
                }
            }
        }
    }
}
