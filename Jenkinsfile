pipeline{
  agent any

  stages {
    stage("front-end"){
      step{
        sh "echo << 'Hello front-end 1'"
      }
      step{
        sh "echo << 'Hello front-end 2'"
      }
    }

    stage("backend-end"){
      step {
        sh "echp << 'Hello!! this is backend 1'"
      }
      step {
        sh "echo << 'Hello!!! this is backend 2'"
      }
    }
  }
}