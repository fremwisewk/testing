#!/usr/bin/env groovy

pipeline {
    agent {
        label 'fake_unix'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying_Testing'
            }
        }
    }
}
