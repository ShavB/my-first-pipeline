pipeline{
  agent any

  stages {
    stage("front-end"){
      steps {
        sh "echo << 'Hello front-end 1'"
      }
      steps {
        sh "echo << 'Hello front-end 2'"
      }
    }

    stage("backend-end"){
      steps {
        sh "echp << 'Hello!! this is backend 1'"
      }
      steps {
        sh "echo << 'Hello!!! this is backend 2'"
      }
    }
  }
}