@Library('belajar-jenkins-shared-library@main') _

import programmerzamannow.jenkins.Output;

pipeline {
  agent any
  stages {
     stage("Hello groovy") {
      steps {
        script {
          Output.hello(this, "Groovy")
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