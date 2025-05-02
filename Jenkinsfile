/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        label 'swarm' // unser Agent im Swarm-Cluster
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building ....'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing ....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying ....'
            }
        }
    }
}
