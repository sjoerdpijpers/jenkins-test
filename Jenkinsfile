#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
