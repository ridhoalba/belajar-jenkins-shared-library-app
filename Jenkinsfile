@Library('belajar-jenkins-shared-library@main') _

import src.programmerzamannow.jenkins.Output;

pipeline {
  agent any
  stages {
     stage("Hello groovy") {
      steps {
        script {
          Output.hello("Groovy")
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