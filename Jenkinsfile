/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        label 'swarm' // unser Agent im Swarm-Cluster
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
