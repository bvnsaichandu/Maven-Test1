pipeline{
    agent any
    stages{
        stage('pacaging the project'){
            steps{
                echo ' maven package '
                bat mvn clean package
                echo ' package is done and release .war file '
            }
            }
        }
    }
}
