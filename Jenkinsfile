#!/usr/bin/env groovy
node {
  stage('Clone repo') {
    // Clones the repository from the current branch name
    echo 'Make the output directory'
    git url: 'https://github.com/fabienp38/test-cypress-jenkins-parallel.git'
  }
  stage('Build  image') {
    // Clones the repository from the current branch name
    checkout scm
    sh 'ls'
  }
}       