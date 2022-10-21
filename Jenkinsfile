#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                echo "Build tag (job_name and build_number: ${env.BUILD_TAG}"
            }
        }
    }
}
