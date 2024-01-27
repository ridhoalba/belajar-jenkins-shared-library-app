@Library('belajar-jenkins-shared-library@main') _

import programmerzamannow.jenkins.Output;

pipeline {
  agent any
  stages {
     stage("Hello groovy") {
      steps {
        script {
          echo Output.hello("Groovy")
        }
      }
    }
    stage("Hello world") {
      steps {
        script {
          hello.world()
        }
      }
    }
  }
}