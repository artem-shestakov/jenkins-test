pipeline {
  environment {
    ENV_FOO = "foo"
  }
  agent any
  stages {
    stage('hello'){
      environment {
        ENV_BAR = "bar"
      }
      steps {
        sh "printenv"
      }
    }
  }
}
