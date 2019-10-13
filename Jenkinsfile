pipeline {
  agent any
  stages {
    stage('Code pull') {
      parallel {
        stage('Code pull') {
          steps {
            sh 'ls'
          }
        }
        stage('check code') {
          steps {
            echo 'code validation'
          }
        }
      }
    }
    stage('build') {
      steps {
        sh 'ls'
      }
    }
    stage('dockerize') {
      parallel {
        stage('dockerize') {
          steps {
            sh 'ls'
          }
        }
        stage('store artifacts') {
          steps {
            echo 'storing jars'
          }
        }
      }
    }
    stage('deploy to test') {
      parallel {
        stage('deploy to test') {
          steps {
            sh 'ls'
          }
        }
        stage('store images') {
          steps {
            echo 'store container images'
          }
        }
      }
    }
  }
}