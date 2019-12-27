#!/bin/groovy
pipeline{
    agent any
    stages {
        stage('Clean Workspace'){
            steps {
                deleteDir()
            }
        }
        stage('SCM Checkout'){
            steps {
                checkout scm
            }
        }
    } 
}
