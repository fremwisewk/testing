#!/usr/bin/env groovy

pipeline {
    
    agent none
    
    stages {
        stage('Build') {
            agent {
                label 'windows'
            }
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            agent {
                label 'windows'
            }
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
