#!/bin/groovy
pipeline{
    agent {
        label 'Linux'
    }
    options {
        skipDefaultCheckout true
        timestamps ()
    }
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
