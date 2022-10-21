#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                echo "Build tag (job_name and build_number): ${env.BUILD_TAG}"
                echo "Build_URL: ${env.BUILD_URL}"
                echo "EXECUTOR_NUMBER: ${env.EXECUTOR_NUMBER}"
                echo "JAVA_HOME: ${env.JAVA_HOME}"
                echo "JENKINS_URL: ${env.JENKINS_URL}"
                echo "JOB_NAME: ${env.JOB_NAME}"
                echo "NODE_NAME: ${env.NODE_NAME}"
                echo "WORKSPACE: ${env.WORKSPACE}"
            }
        }
        stage('second-stage'){
            steps {
                echo "hello second stage"
            }
        }
    }
}
