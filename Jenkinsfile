pipeline{
  agent none
  stages {
    stage("front-end") {
      agent {
        docker { image 'maven:3.8.1-adpotopenjdk-1' }
      }
      steps {
        sh "mvn --version"
      }
    }

    stage("backend-end") {
      agent {
        docker { image 'node:16-alpine' }
      }
      steps {
        sh 'node --version'
      }
    }
  }
}