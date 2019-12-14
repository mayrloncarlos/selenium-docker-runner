pipeline{
    agent any
    stages{
        stage("Run Test"){
            steps{
                bat "docker-compose"
            }
        }
        stage("Bring Grid Down"){
            steps{
                bat "docker-compose down"
            }
        }
    }
}