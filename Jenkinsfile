#!/usr/bin/env groovy
pipeline {
  agent any
  // Start Stages
  stages {
    stage('Clone') {
        // Clones the repository from the current branch name
        echo 'Make the output directory'
        git url: 'https://github.com/fabienp38/test-cypress-jenkins-parallel.git'
    }
  }        
}