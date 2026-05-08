pipeline {
    agent any
    stages {
        stage('build'){
            steps{
                script {
                    sh """
                     echo "Build phase completed"
                    """
                }
            }

        }
        stage('test'){
            steps{
                script {
                    sh """
                     echo "test phase completed"
                    """
                }
            }
            
        }
        stage('deploy'){
            steps{
                script {
                    sh """
                     echo "Deploy    phase completed"
                    """
                }
            }
            
        }
    }
}