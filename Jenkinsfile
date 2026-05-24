pipeline {
    agent any
    stages {
        stage('build'){
            steps{
                script {
                    sh """
                     echo "Build phase completed"
                     echo " Webhook hasbeen added and push"
                    """
                }
            }

        }
        stage('test'){
            steps{
                script {
                    sh """
                     echo "test phase completed"
                     echo " Webhook hasbeen added and push"
                    """
                }
            }
            
        }
        stage('deploy'){
            steps{
                script {
                    sh """
                     echo "Deploy    phase completed"
                     echo " Webhook hasbeen added and push"
                    """
                }
            }
            
        }
    }
}