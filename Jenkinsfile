//Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    //agent { docker { image 'python:3.11.5-alpine3.18' } }
    agent any
    stages {
        stage('build') {
            steps {
              //  bat 'python --version'
                bat echo 'hello world'
            }
        }
    }
}
