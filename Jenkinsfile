#!/bin/bash

// project to display helloworld from jenkins- using jenkins, docker image-creates contianer, 
// erase the container after finishes the execution finishes.
///////////////////////////////////////
pipeline {
  agent {
    docker { image 'alpine' }
  }
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello from Alpine in Docker!'
      }
    }
  }
}

