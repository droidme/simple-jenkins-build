/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        label 'swarm' // unser Agent im Swarm-Cluster
        docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
